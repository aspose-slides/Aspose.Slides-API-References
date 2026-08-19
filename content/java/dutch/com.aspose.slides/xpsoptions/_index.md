---
title: XpsOptions
second_title: Aspose.Slides voor Java API Referentie
description: Biedt opties die regelen hoe een presentatie wordt opgeslagen in XPS-formaat.
type: docs
url: /nl/com.aspose.slides/xpsoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Biedt opties die regelen hoe een presentatie wordt opgeslagen in XPS-formaat.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Maak een Presentation-object aan dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Sla de presentatie op als XPS-document
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Maak een Presentation-object aan dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Maak de TiffOptions-klasse aan
>      XpsOptions options = new XpsOptions();
>      // Sla MetaFiles op als PNG
>      options.setSaveMetafilesAsPng(true);
>      // Sla de presentatie op als XPS-document
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Standaardconstructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Waar om een zwart kader rond elke dia te tekenen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Waar om een zwart kader rond elke dia te tekenen. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Standaardconstructor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**.

**Retourneert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lezen/schrijven boolean.

--------------------

Standaard is **true**.

**Retourneert:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lezen/schrijven boolean.

--------------------

Standaard is **true**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


Waar om een zwart kader rond elke dia te tekenen. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Retourneert:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


Waar om een zwart kader rond elke dia te tekenen. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |