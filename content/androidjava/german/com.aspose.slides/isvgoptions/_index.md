---
title: ISVGOptions
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt eine SVG-Option dar.
type: docs
url: /de/com.aspose.slides/isvgoptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Stellt SVG-Optionen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Gibt die untere Auflösungsgrenze für die Metadatei-Rasterung zurück oder setzt sie. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Gibt die untere Auflösungsgrenze für die Metadatei-Rasterung zurück oder setzt sie. |
| [getDisable3DText()](#getDisable3DText--) | Bestimmt, ob der 3D-Text in SVG deaktiviert ist. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Bestimmt, ob der 3D-Text in SVG deaktiviert ist. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 kann keine Einzüge für Marker definieren. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 kann keine Einzüge für Marker definieren. |
| [getJpegQuality()](#getJpegQuality--) | Bestimmt die JPEG-Codierungsqualität. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Bestimmt die JPEG-Codierungsqualität. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Gibt eine Callback-Schnittstelle zurück und setzt sie, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Gibt eine Callback-Schnittstelle zurück und setzt sie, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht. |
| [getPicturesCompression()](#getPicturesCompression--) | Stellt das Komprimierungslevel für Bilder dar Lesen/Schreiben #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stellt das Komprimierungslevel für Bilder dar Lesen/Schreiben #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. |
| [getUseFrameSize()](#getUseFrameSize--) | Bestimmt, ob der Textrahmen in einen Rendering-Bereich einbezogen wird oder nicht. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Bestimmt, ob der Textrahmen in einen Rendering-Bereich einbezogen wird oder nicht. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt wird oder nicht. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt wird oder nicht. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Bestimmt eine Methode zum Umgang mit extern geladenen Schriftarten. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Bestimmt eine Methode zum Umgang mit extern geladenen Schriftarten. |
| [getInkOptions()](#getInkOptions--) | Stellt Optionen bereit, die das Erscheinungsbild von Ink-Objekten im exportierten Dokument steuern. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Gibt die untere Auflösungsgrenze für die Metadatei-Rasterung zurück oder setzt sie. Lesen/Schreiben int.

**Rückgabewert:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Gibt die untere Auflösungsgrenze für die Metadatei-Rasterung zurück oder setzt sie. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Bestimmt, ob der 3D-Text in SVG deaktiviert ist. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Bestimmt, ob der 3D-Text in SVG deaktiviert ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 kann keine Einzüge für Marker definieren. Die SVG-Schreibengine von Aspose.Slides bietet hierfür eine Problemumgehung: Sie schneidet das Linienende mit Pfeil zu, sodass die Linie die Marker nicht überlappt. Diese Option schaltet dieses Verhalten aus. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 kann keine Einzüge für Marker definieren. Die SVG-Schreibengine von Aspose.Slides bietet hierfür eine Problemumgehung: Sie schneidet das Linienende mit Pfeil zu, sodass die Linie die Marker nicht überlappt. Diese Option schaltet dieses Verhalten aus. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Bestimmt die JPEG-Codierungsqualität. Lesen/Schreiben int.

**Rückgabewert:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Bestimmt die JPEG-Codierungsqualität. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Gibt eine Callback-Schnittstelle zurück und setzt sie, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht. Lesen/Schreiben [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Rückgabewert:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Gibt eine Callback-Schnittstelle zurück und setzt sie, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht. Lesen/Schreiben [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Stellt das Komprimierungslevel für Bilder dar Lesen/Schreiben #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Rückgabewert:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Stellt das Komprimierungslevel für Bilder dar Lesen/Schreiben #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann). Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann). Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Bestimmt, ob der Textrahmen in einen Rendering-Bereich einbezogen wird oder nicht. Lesen/Schreiben boolean. Standardwert ist false.

**Rückgabewert:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Bestimmt, ob der Textrahmen in einen Rendering-Bereich einbezogen wird oder nicht. Lesen/Schreiben boolean. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt wird oder nicht. Lesen/Schreiben boolean. Standardwert ist true.

**Rückgabewert:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt wird oder nicht. Lesen/Schreiben boolean. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Bestimmt eine Methode zum Umgang mit extern geladenen Schriftarten. Lesen/Schreiben [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Rückgabewert:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Bestimmt eine Methode zum Umgang mit extern geladenen Schriftarten. Lesen/Schreiben [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Stellt Optionen bereit, die das Erscheinungsbild von Ink-Objekten im exportierten Dokument steuern. Nur-Lesen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabewert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |