---
title: SVGOptions
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt SVG-Optionen dar.
type: docs
url: /de/com.aspose.slides/svgoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Stellt SVG-Optionen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Initialisiert eine neue Instanz der SVGOptions-Klasse. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Initialisiert eine neue Instanz der SVGOptions-Klasse und gibt das Link-Embedding-Controller-Objekt an. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |
| [getUseFrameSize()](#getUseFrameSize--) | Bestimmt, ob der Textrahmen in einem Rendering-Bereich enthalten sein soll oder nicht. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Bestimmt, ob der Textrahmen in einem Rendering-Bereich enthalten sein soll oder nicht. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt werden soll oder nicht. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt werden soll oder nicht. |
| [getVectorizeText()](#getVectorizeText--) | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder setzt sie. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder setzt sie. |
| [getDisable3DText()](#getDisable3DText--) | Bestimmt, ob 3D-Text in SVG deaktiviert ist. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Bestimmt, ob 3D-Text in SVG deaktiviert ist. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 kann keine Einfügungen für Marker definieren. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 kann keine Einfügungen für Marker definieren. |
| [getDefault()](#getDefault--) | Gibt die Standardeinstellungen zurück. |
| [getSimple()](#getSimple--) | Gibt Einstellungen für die einfachste und kleinste SVG-Dateigenerierung zurück. |
| [getWYSIWYG()](#getWYSIWYG--) | Gibt Einstellungen für die genaueste SVG-Dateigenerierung zurück. |
| [getJpegQuality()](#getJpegQuality--) | Bestimmt die JPEG-Kodierungsqualität. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Bestimmt die JPEG-Kodierungsqualität. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Gibt eine Callback-Schnittstelle zurück und setzt sie, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Gibt eine Callback-Schnittstelle zurück und setzt sie, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. |
| [getPicturesCompression()](#getPicturesCompression--) | Stellt das Komprimierungsniveau der Bilder dar |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stellt das Komprimierungsniveau der Bilder dar |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Ein boolesches Flag zeigt an, ob die abgeschnittenen Teile Teil des Dokuments bleiben. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Ein boolesches Flag zeigt an, ob die abgeschnittenen Teile Teil des Dokuments bleiben. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Bestimmt, wie extern geladene Schriftarten behandelt werden. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Bestimmt, wie extern geladene Schriftarten behandelt werden. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Initialisiert eine neue Instanz der SVGOptions-Klasse.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Initialisiert eine neue Instanz der SVGOptions-Klasse und gibt das Link-Embedding-Controller-Objekt an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Die Referenz des Link-Embedding-Controllers. |

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |
### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur-Lesen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabewert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Bestimmt, ob der Textrahmen in einem Rendering-Bereich enthalten sein soll oder nicht. Lesen/Schreiben boolean. Standardwert ist false.

**Rückgabewert:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Bestimmt, ob der Textrahmen in einem Rendering-Bereich enthalten sein soll oder nicht. Lesen/Schreiben boolean. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt werden soll oder nicht. Lesen/Schreiben boolean. Standardwert ist true.

**Rückgabewert:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt werden soll oder nicht. Lesen/Schreiben boolean. Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder setzt sie. Lesen/Schreiben int.

**Rückgabewert:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder setzt sie. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Bestimmt, ob 3D-Text in SVG deaktiviert ist. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Bestimmt, ob 3D-Text in SVG deaktiviert ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 kann keine Einfügungen für Marker definieren. Der SVG-Schreib-Engine von Aspose.Slides hat eine Lösung für dieses Problem: Sie schneidet das Linienende mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option deaktiviert dieses Verhalten. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 kann keine Einfügungen für Marker definieren. Der SVG-Schreib-Engine von Aspose.Slides hat eine Lösung für dieses Problem: Sie schneidet das Linienende mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option deaktiviert dieses Verhalten. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Gibt die Standardeinstellungen zurück. Nur-Lesen [SVGOptions](../../com.aspose.slides/svgoptions).

**Rückgabewert:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Gibt Einstellungen für die einfachste und kleinste SVG-Dateigenerierung zurück. Nur-Lesen [SVGOptions](../../com.aspose.slides/svgoptions).

**Rückgabewert:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Gibt Einstellungen für die genaueste SVG-Dateigenerierung zurück. Nur-Lesen [SVGOptions](../../com.aspose.slides/svgoptions).

**Rückgabewert:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Bestimmt die JPEG-Kodierungsqualität. Lesen/Schreiben int.

**Rückgabewert:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Bestimmt die JPEG-Kodierungsqualität. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Gibt eine Callback-Schnittstelle zurück und setzt sie, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Lesen/Schreiben [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Rückgabewert:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Gibt eine Callback-Schnittstelle zurück und setzt sie, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Lesen/Schreiben [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Stellt das Komprimierungsniveau der Bilder dar

**Rückgabewert:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Stellt das Komprimierungsniveau der Bilder dar

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Ein boolesches Flag zeigt an, ob die abgeschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die abgeschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann)

**Rückgabewert:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Ein boolesches Flag zeigt an, ob die abgeschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die abgeschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann)

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Bestimmt, wie extern geladene Schriftarten behandelt werden. Lesen/Schreiben [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Rückgabewert:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Bestimmt, wie extern geladene Schriftarten behandelt werden. Lesen/Schreiben [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Beispiel:
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
public final void setDisableFontLigatures(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Beispiel:
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