---
title: ISVGOptions
second_title: Aspose.Slides für Java API-Referenz
description: Stellt SVG-Optionen dar.
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
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest. |
| [getDisable3DText()](#getDisable3DText--) | Bestimmt, ob 3D-Text in SVG deaktiviert ist. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Bestimmt, ob 3D-Text in SVG deaktiviert ist. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 kann keine Einrückungen für Marker definieren. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 kann keine Einrückungen für Marker definieren. |
| [getJpegQuality()](#getJpegQuality--) | Bestimmt die JPEG-Kodierungsqualität. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Bestimmt die JPEG-Kodierungsqualität. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Gibt eine Callback-Schnittstelle zurück und legt sie fest, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Gibt eine Callback-Schnittstelle zurück und legt sie fest, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. |
| [getPicturesCompression()](#getPicturesCompression--) | Stellt das Bildkomprimierungsniveau dar Lesen/Schreiben \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stellt das Bildkomprimierungsniveau dar Lesen/Schreiben \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. |
| [getUseFrameSize()](#getUseFrameSize--) | Bestimmt, ob der Textrahmen in einen Renderbereich aufgenommen wird oder nicht. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Bestimmt, ob der Textrahmen in einen Renderbereich aufgenommen wird oder nicht. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt wird oder nicht. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt wird oder nicht. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Bestimmt, wie extern geladene Schriftarten behandelt werden. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Bestimmt, wie extern geladene Schriftarten behandelt werden. |
| [getInkOptions()](#getInkOptions--) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen gerendert wird. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest. Lesen/Schreiben int.

**Rückgabe:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Bestimmt, ob 3D-Text in SVG deaktiviert ist. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Bestimmt, ob 3D-Text in SVG deaktiviert ist. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 kann keine Einrückungen für Marker definieren. Aspose.Slides SVG-Schreibengine hat einen Workaround für dieses Problem: Sie schneidet das Linienende mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option deaktiviert dieses Verhalten. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 kann keine Einrückungen für Marker definieren. Aspose.Slides SVG-Schreibengine hat einen Workaround für dieses Problem: Sie schneidet das Linienende mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option deaktiviert dieses Verhalten. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Bestimmt die JPEG-Kodierungsqualität. Lesen/Schreiben int.

**Rückgabe:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Bestimmt die JPEG-Kodierungsqualität. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Gibt eine Callback-Schnittstelle zurück und legt sie fest, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Lesen/Schreiben [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Rückgabe:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Gibt eine Callback-Schnittstelle zurück und legt sie fest, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Lesen/Schreiben [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Stellt das Bildkomprimierungsniveau dar Lesen/Schreiben \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Rückgabe:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Stellt das Bildkomprimierungsniveau dar Lesen/Schreiben \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, bleiben sie im Dokument serialisiert (was zu einer größeren Datei führen kann). Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, bleiben sie im Dokument serialisiert (was zu einer größeren Datei führen kann). Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Bestimmt, ob der Textrahmen in einen Renderbereich aufgenommen wird oder nicht. Lesen/Schreiben boolesch. Standardwert ist false.

**Rückgabe:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Bestimmt, ob der Textrahmen in einen Renderbereich aufgenommen wird oder nicht. Lesen/Schreiben boolesch. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt wird oder nicht. Lesen/Schreiben boolesch. Standardwert ist true.

**Rückgabe:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt wird oder nicht. Lesen/Schreiben boolesch. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Bestimmt, wie extern geladene Schriftarten behandelt werden. Lesen/Schreiben [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Rückgabe:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Bestimmt, wie extern geladene Schriftarten behandelt werden. Lesen/Schreiben [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur-Lesen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabe:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn true, werden Ligaturen im gerenderten Ausgabe deaktiviert. Standardmäßig ist dieser Wert false.

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


**Rückgabe:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn true, werden Ligaturen im gerenderten Ausgabe deaktiviert. Standardmäßig ist dieser Wert false.

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