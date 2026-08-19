---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Tillhandahåller enkel åtkomst till innehållna hyperlänkar.
type: docs
url: /sv/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Tillhandahåller enkel åtkomst till innehållna hyperlänkar.
## Metoder

| Method | Description |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Hämta alla IHyperlinkContainer-underdelar som innehåller en icke-null HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Hämta alla IHyperlinkContainer-underdelar som innehåller en icke-null HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Hämta alla IHyperlinkContainer-underdelar som innehåller en icke-null HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Tar bort alla inbäddade HyperlinkClick- och HyperlinkMouseOver-hyperlänkar (i alla IHyperlinkContainer-underdelar). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Hämta alla IHyperlinkContainer-underdelar som innehåller en icke-null HyperlinkClick. Med ett givet IHyperlinkContainer-objekt kan du hantera dess hyperlänk (läsa, uppdatera eller ta bort). Se IHyperlinkContainer-gränssnittet.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alla IHyperlinkContainer-underdelar som innehåller en icke-null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Hämta alla IHyperlinkContainer-underdelar som innehåller en icke-null HyperlinkMouseOver. Med ett givet IHyperlinkContainer-objekt kan du hantera dess hyperlänk (läsa, uppdatera eller ta bort). Se IHyperlinkContainer-gränssnittet.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alla IHyperlinkContainer-underdelar som innehåller en icke-null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Hämta alla IHyperlinkContainer-underdelar som innehåller en icke-null HyperlinkMouseOver. Med ett givet IHyperlinkContainer-objekt kan du hantera dess hyperlänk (läsa, uppdatera eller ta bort). Se IHyperlinkContainer-gränssnittet.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alla IHyperlinkContainer-underdelar som innehåller en icke-null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```


Tar bort alla inbäddade HyperlinkClick- och HyperlinkMouseOver-hyperlänkar (i alla IHyperlinkContainer-underdelar).