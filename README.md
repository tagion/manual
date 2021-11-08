# Manual

> **Important!**  
> This manual is **work in progress**, it needs

## Versioning

**Alpha** and **Beta** versions consist only of two digits: `1.0.alpha`, `1.5.beta` or `2.3.alpha`. We also have a shortcut `alpha` branch that always points to the latest alpha.

**Stable** versions have normal [semver](https://semver.org/) specification: `1.0.1` or `2.3.4`.

New set of features always starts with **alpha** version. When the work is done, it is promoted to **beta** and is closed for any modifications except big fixes.

After **beta** version passed all automatic and manual tests, it is promoted to **stable** version, e.g., `2.3.0`. At this stage, only patches are allowed, and every patch must increment thrid version digit, e.g., `2.3.1`.

## Branching

Before you modify anything, you must branch from a specific alpha version and name your branch according to your username, e.g., `1.0.jd` or `1.4.peppa`, ~~if you are a pig~~.

- If you branch from `1.0.alpha`, your working branch must be named `1.0.<jd>`.
- If you branch from stable `1.5.8`, you working branch must be named `1.5.8.<jd>`.

**Important!** You should only branch from **stable** or **beta** to make a patch. All new features, or refactors must be initiated from **alpha** branches.