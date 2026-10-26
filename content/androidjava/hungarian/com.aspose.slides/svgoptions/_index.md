---
title: SVGOptions
second_title: Aspose.Slides Androidra a Java API hivatkozással
description: SVG beállításokat képvisel.
type: docs
url: /hu/com.aspose.slides/svgoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

SVG beállításokat képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Új példányt hoz létre a SVGOptions osztályból. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Új példányt hoz létre a SVGOptions osztályból, megadva a link beágyazási vezérlő objektumot. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
| [getUseFrameSize()](#getUseFrameSize--) | Meghatározza, hogy a szövegkeret bele legyen-e foglalva a renderelési területbe, vagy sem. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Meghatározza, hogy a szövegkeret bele legyen-e foglalva a renderelési területbe, vagy sem. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Meghatározza, hogy a megadott forgatás alkalmazásra kerüljön-e a alakzatra rendereléskor, vagy sem. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Meghatározza, hogy a megadott forgatás alkalmazásra kerüljön-e a alakzatra rendereléskor, vagy sem. |
| [getVectorizeText()](#getVectorizeText--) | Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Visszaadja vagy beállítja a metafájl rasterizálás alacsony felbontású határértékét. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Visszaadja vagy beállítja a metafájl rasterizálás alacsony felbontású határértékét. |
| [getDisable3DText()](#getDisable3DText--) | Meghatározza, hogy a 3D szöveg ki legyen-e kapcsolva az SVG-ben. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Meghatározza, hogy a 3D szöveg ki legyen-e kapcsolva az SVG-ben. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Letiltja a FromCornerX és a FromCenter gradientek felosztását. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Letiltja a FromCornerX és a FromCenter gradientek felosztását. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | Az SVG 1.1 nem támogatja a jelölők belső margóinak definiálását. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | Az SVG 1.1 nem támogatja a jelölők belső margóinak definiálását. |
| [getDefault()](#getDefault--) | Visszaadja az alapértelmezett beállításokat. |
| [getSimple()](#getSimple--) | Visszaadja a legegyszerűbb és legkisebb SVG fájl generálásához szükséges beállításokat. |
| [getWYSIWYG()](#getWYSIWYG--) | Visszaadja a legpontosabb SVG fájl generálásához szükséges beállításokat. |
| [getJpegQuality()](#getJpegQuality--) | Meghatározza a JPEG kódolás minőségét. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Meghatározza a JPEG kódolás minőségét. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Visszaad és beállít egy visszahívási interfészt, amely lehetővé teszi a felhasználó számára az alakzat konverziójának vezérlését. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Visszaad és beállít egy visszahívási interfészt, amely lehetővé teszi a felhasználó számára az alakzat konverziójának vezérlését. |
| [getPicturesCompression()](#getPicturesCompression--) | A képek tömörítési szintjét képviseli |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | A képek tömörítési szintjét képviseli |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Egy logikai jelző jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Egy logikai jelző jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Visszaadja vagy beállítja azt az értéket, amely meghatározza, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Visszaadja vagy beállítja azt az értéket, amely meghatározza, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Új példányt hoz létre a SVGOptions osztályból.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Új példányt hoz létre a SVGOptions osztályból, megadva a link beágyazási vezérlő objektumot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | A link beágyazási vezérlő referenciája. |

Link embedding controller egy delegált objektum, amely felelős annak eldöntéséért, hogy a források (például képek) be legyenek-e ágyazva, vagy külső erőforrásként hivatkozottak.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatérési érték:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Meghatározza, hogy a szövegkeret bele legyen-e foglalva a renderelési területbe, vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: false.

**Visszatérési érték:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Meghatározza, hogy a szövegkeret bele legyen-e foglalva a renderelési területbe, vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Meghatározza, hogy a megadott forgatás alkalmazásra kerüljön-e a alakzatra rendereléskor, vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Meghatározza, hogy a megadott forgatás alkalmazásra kerüljön-e a alakzatra rendereléskor, vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Visszaadja vagy beállítja a metafájl rasterizálás alacsony felbontású határértékét. Olvasás/írás int.

**Visszatérési érték:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Visszaadja vagy beállítja a metafájl rasterizálás alacsony felbontású határértékét. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Meghatározza, hogy a 3D szöveg ki legyen-e kapcsolva az SVG-ben. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Meghatározza, hogy a 3D szöveg ki legyen-e kapcsolva az SVG-ben. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Letiltja a FromCornerX és a FromCenter gradientek felosztását. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Letiltja a FromCornerX és a FromCenter gradientek felosztását. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

Az SVG 1.1 nem támogatja a jelölők belső margóinak meghatározását. Az Aspose.Slides SVG író motorja megoldást kínál erre a problémára: levágja a vonal végét a nyíllal, így a vonal nem fed át a jelölőket. Ez a beállítás kikapcsolja ezt a viselkedést. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

Az SVG 1.1 nem támogatja a jelölők belső margóinak meghatározását. Az Aspose.Slides SVG író motorja megoldást kínál erre a problémára: levágja a vonal végét a nyíllal, így a vonal nem fed át a jelölőket. Ez a beállítás kikapcsolja ezt a viselkedést. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Visszaadja az alapértelmezett beállításokat. Csak olvasható [SVGOptions](../../com.aspose.slides/svgoptions).

**Visszatérési érték:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Visszaadja a legegyszerűbb és legkisebb SVG fájl generálásához szükséges beállításokat. Csak olvasható [SVGOptions](../../com.aspose.slides/svgoptions).

**Visszatérési érték:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Visszaadja a legpontosabb SVG fájl generálásához szükséges beállításokat. Csak olvasható [SVGOptions](../../com.aspose.slides/svgoptions).

**Visszatérési érték:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Meghatározza a JPEG kódolás minőségét. Olvasás/írás int.

**Visszatérési érték:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Meghatározza a JPEG kódolás minőségét. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Visszaad és beállít egy visszahívási interfészt, amely lehetővé teszi a felhasználó számára az alakzat konverziójának vezérlését. Olvasás/írás [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Visszatérési érték:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Visszaad és beállít egy visszahívási interfészt, amely lehetővé teszi a felhasználó számára az alakzat konverziójának vezérlését. Olvasás/írás [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

A képek tömörítési szintjét képviseli

**Visszatérési érték:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

A képek tömörítési szintjét képviseli

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Egy logikai jelző jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban lesznek sorosítva (ami esetleg nagyobb fájlméretet eredményezhet).

**Visszatérési érték:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Egy logikai jelző jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban lesznek sorosítva (ami esetleg nagyobb fájlméretet eredményezhet).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. Olvasás/írás [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Visszatérési érték:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. Olvasás/írás [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Visszaadja vagy beállítja azt az értéket, amely meghatározza, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve. Ha igazra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság hamis.

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


**Visszatérési érték:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Visszaadja vagy beállítja azt az értéket, amely meghatározza, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve. Ha igazra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság hamis.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |