---
title: IHyperlinkQueries
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller enkel åtkomst till innehållna hyperlänkar.
type: docs
url: /sv/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Tillhandahåller enkel åtkomst till innehållna hyperlänkar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Hämta alla IHyperlinkContainer-delobjekt som innehåller ett icke-null HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Hämta alla IHyperlinkContainer-delobjekt som innehåller ett icke-null HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Hämta alla IHyperlinkContainer-delobjekt som innehåller ett icke-null HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Tar bort alla innehållna HyperlinkClick- och HyperlinkMouseOver-hyperlänkar (i alla IHyperlinkContainer-delobjekt). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Hämta alla IHyperlinkContainer-delobjekt som innehåller ett icke-null HyperlinkClick. Med ett givet IHyperlinkContainer-objekt kan du hantera dess hyperlänk (läsa, uppdatera eller ta bort). Se IHyperlinkContainer-gränssnittet.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alla IHyperlinkContainer-delobjekt som innehåller ett icke-null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Hämta alla IHyperlinkContainer-delobjekt som innehåller ett icke-null HyperlinkMouseOver. Med ett givet IHyperlinkContainer-objekt kan du hantera dess hyperlänk (läsa, uppdatera eller ta bort). Se IHyperlinkContainer-gränssnittet.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alla IHyperlinkContainer-delobjekt som innehåller ett icke-null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Hämta alla IHyperlinkContainer-delobjekt som innehåller ett icke-null HyperlinkMouseOver. Med ett givet IHyperlinkContainer-objekt kan du hantera dess hyperlänk (läsa, uppdatera eller ta bort). Se IHyperlinkContainer-gränssnittet.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alla IHyperlinkContainer-delobjekt som innehåller ett icke-null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Tar bort alla innehållna HyperlinkClick- och HyperlinkMouseOver-hyperlänkar (i alla IHyperlinkContainer-delobjekt).