---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Bied gemakkelijke toegang tot ingesloten hyperlinks.
type: docs
url: /nl/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Bied gemakkelijke toegang tot ingesloten hyperlinks.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Removes all contained HyperlinkClick and HyperlinkMouseOver hyperlinks (in all IHyperlinkContainer subobjects). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Geef alle IHyperlinkContainer subobjecten die een niet-null HyperlinkClick bevatten. Met het opgegeven IHyperlinkContainer-object kunt u de hyperlink beheren (lezen, bijwerken of verwijderen). Zie IHyperlinkContainer-interface.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer subobjecten die een niet-null HyperlinkClick bevatten
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Geef alle IHyperlinkContainer subobjecten die een niet-null HyperlinkMouseOver bevatten. Met het opgegeven IHyperlinkContainer-object kunt u de hyperlink beheren (lezen, bijwerken of verwijderen). Zie IHyperlinkContainer-interface.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer subobjecten die een niet-null HyperlinkMouseOver bevatten
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Geef alle IHyperlinkContainer subobjecten die een niet-null HyperlinkMouseOver bevatten. Met het opgegeven IHyperlinkContainer-object kunt u de hyperlink beheren (lezen, bijwerken of verwijderen). Zie IHyperlinkContainer-interface.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer subobjecten die een niet-null HyperlinkMouseOver bevatten
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```


Verwijdert alle ingesloten HyperlinkClick- en HyperlinkMouseOver-hyperlinks (in alle IHyperlinkContainer subobjecten).