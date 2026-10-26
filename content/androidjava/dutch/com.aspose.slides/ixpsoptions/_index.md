---
title: IXpsOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in XPS-formaat.
type: docs
url: /nl/com.aspose.slides/ixpsoptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in XPS format.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True om alle metafiles die in een presentatie worden gebruikt naar PNG-afbeeldingen te converteren. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True om alle metafiles die in een presentatie worden gebruikt naar PNG-afbeeldingen te converteren. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True om een zwart kader rond elke dia te tekenen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True om een zwart kader rond elke dia te tekenen. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


True om alle metafiles die in een presentatie worden gebruikt naar PNG-afbeeldingen te converteren. Lezen/Schrijven boolean.

--------------------

Default is **true**.

**Retour:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


True om alle metafiles die in een presentatie worden gebruikt naar PNG-afbeeldingen te converteren. Lezen/Schrijven boolean.

--------------------

Default is **true**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


True om een zwart kader rond elke dia te tekenen. Lezen/Schrijven boolean.

--------------------

Default is **false**.

**Retour:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


True om een zwart kader rond elke dia te tekenen. Lezen/Schrijven boolean.

--------------------

Default is **false**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. Default is false.

**Retour:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. Default is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |