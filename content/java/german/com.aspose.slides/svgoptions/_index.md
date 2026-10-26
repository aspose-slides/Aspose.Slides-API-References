---
title: SVGOptions
second_title: Aspose.Slides für Java API-Referenz
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

Stellt eine SVG-Option dar.
## Constructors

| Konstruktor | Beschreibung |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Initialisiert eine neue Instanz der Klasse SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Initialisiert eine neue Instanz der Klasse SVGOptions und gibt das Link-Einbettungs-Controller-Objekt an. |
## Methods

| Methode | Beschreibung |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |
| [getUseFrameSize()](#getUseFrameSize--) | Bestimmt, ob der Textrahmen in einen Renderbereich einbezogen wird oder nicht. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Bestimmt, ob der Textrahmen in einen Renderbereich einbezogen wird oder nicht. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt wird oder nicht. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt wird oder nicht. |
| [getVectorizeText()](#getVectorizeText--) | Bestimmt, ob der Text auf einer Folie als Grafiken gespeichert wird. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Bestimmt, ob der Text auf einer Folie als Grafiken gespeichert wird. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest. |
| [getDisable3DText()](#getDisable3DText--) | Bestimmt, ob 3D-Text in SVG deaktiviert ist. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Bestimmt, ob 3D-Text in SVG deaktiviert ist. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 kann keine Einzüge für Markierungen definieren. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 kann keine Einzüge für Markierungen definieren. |
| [getDefault()](#getDefault--) | Gibt Standardeinstellungen zurück. |
| [getSimple()](#getSimple--) | Gibt Einstellungen für die einfachste und kleinste SVG-Dateigenerierung zurück. |
| [getWYSIWYG()](#getWYSIWYG--) | Gibt Einstellungen für die genaueste SVG-Dateigenerierung zurück. |
| [getJpegQuality()](#getJpegQuality--) | Bestimmt die JPEG-Kodierungsqualität. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Bestimmt die JPEG-Kodierungsqualität. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Gibt eine Callback-Schnittstelle zurück und legt sie fest, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Gibt eine Callback-Schnittstelle zurück und legt sie fest, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht. |
| [getPicturesCompression()](#getPicturesCompression--) | Stellt das Komprimierungsniveau für Bilder dar. |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stellt das Komprimierungsniveau für Bilder dar. |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Bestimmt, wie extern geladene Schriftarten behandelt werden. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Bestimmt, wie extern geladene Schriftarten behandelt werden. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Initialisiert eine neue Instanz der Klasse SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Initialisiert eine neue Instanz der Klasse SVGOptions und gibt das Link-Einbettungs-Controller-Objekt an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Die Referenz auf den Link-Einbettungs-Controller. |

--------------------

Der Link-Einbettungs-Controller ist ein Delegat-Objekt, das für Entscheidungen verantwortlich ist, ob Ressourcen (wie Bilder) eingebettet oder als externe Ressourcen referenziert werden müssen.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur-Lesen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabe:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Bestimmt, ob der Textrahmen in einen Renderbereich einbezogen wird oder nicht. Lesen/Schreiben boolean . Standardwert ist false.

**Rückgabe:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Bestimmt, ob der Textrahmen in einen Renderbereich einbezogen wird oder nicht. Lesen/Schreiben boolean . Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt wird oder nicht. Lesen/Schreiben boolean . Standardwert ist true.

**Rückgabe:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Bestimmt, ob die angegebene Drehung der Form beim Rendern durchgeführt wird oder nicht. Lesen/Schreiben boolean . Standardwert ist true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Bestimmt, ob der Text auf einer Folie als Grafiken gespeichert wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Bestimmt, ob der Text auf einer Folie als Grafiken gespeichert wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest. Lesen/Schreiben int.

**Rückgabe:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Bestimmt, ob 3D-Text in SVG deaktiviert ist. Lesen/Schreiben boolean.

**Rückgabe:**
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

**Rückgabe:**
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

SVG 1.1 kann keine Einzüge für Markierungen definieren. Die SVG-Schreibengine von Aspose.Slides hat dafür eine Lösung: Sie kürzt das Ende einer Linie mit Pfeil, so dass die Linie nicht mit Markierungen überlappt. Diese Option schaltet dieses Verhalten aus. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 kann keine Einzüge für Markierungen definieren. Die SVG-Schreibengine von Aspose.Slides hat dafür eine Lösung: Sie kürzt das Ende einer Linie mit Pfeil, so dass die Linie nicht mit Markierungen überlappt. Diese Option schaltet dieses Verhalten aus. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Gibt Standardeinstellungen zurück. Nur-Lesen [SVGOptions](../../com.aspose.slides/svgoptions).

**Rückgabe:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Gibt Einstellungen für die einfachste und kleinste SVG-Dateigenerierung zurück. Nur-Lesen [SVGOptions](../../com.aspose.slides/svgoptions).

**Rückgabe:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Gibt Einstellungen für die genaueste SVG-Dateigenerierung zurück. Nur-Lesen [SVGOptions](../../com.aspose.slides/svgoptions).

**Rückgabe:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Bestimmt die JPEG-Kodierungsqualität. Lesen/Schreiben int.

**Rückgabe:**
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

Gibt eine Callback-Schnittstelle zurück und legt sie fest, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht. Lesen/Schreiben [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Rückgabe:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Gibt eine Callback-Schnittstelle zurück und legt sie fest, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht. Lesen/Schreiben [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Stellt das Komprimierungsniveau für Bilder dar.

**Rückgabe:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Stellt das Komprimierungsniveau für Bilder dar.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann).

**Rückgabe:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Bestimmt, wie extern geladene Schriftarten gehandhabt werden. Lesen/Schreiben [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Rückgabe:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Bestimmt, wie extern geladene Schriftarten gehandhabt werden. Lesen/Schreiben [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

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
public final void setDisableFontLigatures(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

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