---
title: IHyperlinkQueries
second_title: Aspose.Slides voor Android via Java API-referentie
description: Bied gemakkelijke toegang tot de ingesloten hyperlinks.
type: docs
url: /nl/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Bied gemakkelijke toegang tot de ingesloten hyperlinks.
## Methods

| Method | Description |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Haal alle IHyperlinkContainer-subobjecten op die een niet-nul HyperlinkClick bevatten. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Haal alle IHyperlinkContainer-subobjecten op die een niet-nul HyperlinkMouseOver bevatten. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Haal alle IHyperlinkContainer-subobjecten op die een niet-nul HyperlinkMouseOver bevatten. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Verwijdert alle ingesloten HyperlinkClick- en HyperlinkMouseOver-hyperlinks (in alle IHyperlinkContainer-subobjecten). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Haal alle IHyperlinkContainer-subobjecten op die een niet-nul HyperlinkClick bevatten. Met een gegeven IHyperlinkContainer-object kunt u de hyperlink beheren (lezen, bijwerken of verwijderen). Zie de IHyperlinkContainer-interface.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer-subobjecten die een niet-nul HyperlinkClick bevatten
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Haal alle IHyperlinkContainer-subobjecten op die een niet-nul HyperlinkMouseOver bevatten. Met een gegeven IHyperlinkContainer-object kunt u de hyperlink beheren (lezen, bijwerken of verwijderen). Zie de IHyperlinkContainer-interface.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer-subobjecten die een niet-nul HyperlinkMouseOver bevatten
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Haal alle IHyperlinkContainer-subobjecten op die een niet-nul HyperlinkMouseOver bevatten. Met een gegeven IHyperlinkContainer-object kunt u de hyperlink beheren (lezen, bijwerken of verwijderen). Zie de IHyperlinkContainer-interface.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer-subobjecten die een niet-nul HyperlinkMouseOver bevatten
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Verwijdert alle ingesloten HyperlinkClick- en HyperlinkMouseOver-hyperlinks (in alle IHyperlinkContainer-subobjecten).