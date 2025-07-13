# A Theme for Revealjs Presentations

## Installing

```bash
quarto use template swinnoproject/swinno_revealjs
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

To use the template with an existing presentation use

```bash
quarto install extension swinnoproject/swinno_revealjs
```

## Usage

```yaml
---
title: A title
subtitle: A subtitle
format:
  swinnoproject/swinno_revealjs-revealjs: default
author:
  - name: First Last
    orcid: 0000-0000-0000-0000
    email: alias@email.com
    affiliations: Your Institution
date: last-modified
---

```
