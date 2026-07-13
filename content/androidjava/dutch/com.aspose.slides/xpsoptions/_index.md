---
title: XpsOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in XPS-formaat.
type: docs
url: /nl/com.aspose.slides/xpsoptions/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in XPS-formaat.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
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
>  // Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Instantieer de TiffOptions-klasse
>      XpsOptions options = new XpsOptions();
>      // Sla MetaFiles op als PNG
>      options.setSaveMetafilesAsPng(true);
>      // Sla de presentatie op als XPS-document
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Standaardconstructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True om een zwart kader rond elke dia te tekenen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True om een zwart kader rond elke dia te tekenen. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Standaardconstructor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Retour:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lees/Schrijf boolean.

--------------------

Standaard is **true**.

**Retour:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lees/Schrijf boolean.

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

True om een zwart kader rond elke dia te tekenen. Lees/Schrijf boolean.

--------------------

Standaard is **false**.

**Retour:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True om een zwart kader rond elke dia te tekenen. Lees/Schrijf boolean.

--------------------

Standaard is **false**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |