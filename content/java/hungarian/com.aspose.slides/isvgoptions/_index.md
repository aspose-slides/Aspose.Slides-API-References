---
title: ISVGOptions
second_title: Aspose.Slides for Java API referencia
description: SVG opciókat képvisel.
type: docs
url: /hu/com.aspose.slides/isvgoptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Az SVG opciókat képviseli.
## Methods

| Method | Description |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Meghatározza, hogy a dián lévő szöveget grafikai objektumként menti-e. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Meghatározza, hogy a dián lévő szöveget grafikai objektumként menti-e. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Visszaadja vagy beállítja a metafájl rasterizálásának alsó felbontási korlátját. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Visszaadja vagy beállítja a metafájl rasterizálásának alsó felbontási korlátját. |
| [getDisable3DText()](#getDisable3DText--) | Meghatározza, hogy a 3D szöveg le van-e tiltva az SVG-ben. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Meghatározza, hogy a 3D szöveg le van-e tiltva az SVG-ben. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Letiltja a FromCornerX és FromCenter gradientek felosztását. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Letiltja a FromCornerX és FromCenter gradientek felosztását. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | Az SVG 1.1 nem támogatja a markerek beállításának definiálását. Az Aspose.Slides SVG írómotor megoldást kínál: levágja a nyíllal ellátott vonal végét, így a vonal nem fed le marker-eket. Ez a beállítás kikapcsolja ezt a viselkedést. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | Az SVG 1.1 nem támogatja a markerek beállításának definiálását. Az Aspose.Slides SVG írómotor megoldást kínál: levágja a nyíllal ellátott vonal végét, így a vonal nem fed le marker-eket. Ez a beállítás kikapcsolja ezt a viselkedést. |
| [getJpegQuality()](#getJpegQuality--) | Meghatározza a JPEG kódolás minőségét. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Meghatározza a JPEG kódolás minőségét. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a forma konverziójának vezérlését. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a forma konverziójának vezérlését. |
| [getPicturesCompression()](#getPicturesCompression--) | A képek tömörítési szintjét képviseli Olvasás/írás \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | A képek tömörítési szintjét képviseli Olvasás/írás \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Egy logikai jelző, amely azt jelzi, hogy a levágott részek a dokumentum részét képezik-e. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Egy logikai jelző, amely azt jelzi, hogy a levágott részek a dokumentum részét képezik-e. |
| [getUseFrameSize()](#getUseFrameSize--) | Meghatározza, hogy a szövegdoboz szerepel-e a renderelési területen vagy sem. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Meghatározza, hogy a szövegdoboz szerepel-e a renderelési területen vagy sem. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Meghatározza, hogy a forma megadott forgatása a renderelés során végrehajtásra kerül-e vagy sem. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Meghatározza, hogy a forma megadott forgatása a renderelés során végrehajtásra kerül-e vagy sem. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Meghatározza a külsőleg betöltött betűkészletek kezelésének módját. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Meghatározza a külsőleg betöltött betűkészletek kezelésének módját. |
| [getInkOptions()](#getInkOptions--) | Olyan opciókat biztosít, amelyek az exportált dokumentumban lévő Ink objektumok megjelenését szabályozzák. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Megkap vagy beállít egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Megkap vagy beállít egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```


Meghatározza, hogy a dián lévő szöveget grafikai objektumként menti-e. Olvasás/írás boolean.

**Visszatér:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```


Meghatározza, hogy a dián lévő szöveget grafikai objektumként menti-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```


Visszaadja vagy beállítja a metafájl rasterizálásának alsó felbontási korlátját. Olvasás/írás int.

**Visszatér:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```


Visszaadja vagy beállítja a metafájl rasterizálásának alsó felbontási korlátját. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```


Meghatározza, hogy a 3D szöveg le van-e tiltva az SVG-ben. Olvasás/írás boolean.

**Visszatér:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```


Meghatározza, hogy a 3D szöveg le van-e tiltva az SVG-ben. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```


Letiltja a FromCornerX és FromCenter gradientek felosztását. Olvasás/írás boolean.

**Visszatér:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```


Letiltja a FromCornerX és FromCenter gradientek felosztását. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```


Az SVG 1.1 nem támogatja a markerek beállításának definiálását. Az Aspose.Slides SVG írómotor megoldást kínál: levágja a nyíllal ellátott vonal végét, így a vonal nem fed le marker-eket. Ez a beállítás kikapcsolja ezt a viselkedést. Olvasás/írás boolean.

**Visszatér:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```


Az SVG 1.1 nem támogatja a markerek beállításának definiálását. Az Aspose.Slides SVG írómotor megoldást kínál: levágja a nyíllal ellátott vonal végét, így a vonal nem fed le marker-eket. Ez a beállítás kikapcsolja ezt a viselkedést. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```


Meghatározza a JPEG kódolás minőségét. Olvasás/írás int.

**Visszatér:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```


Meghatározza a JPEG kódolás minőségét. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```


Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a forma konverziójának vezérlését. Olvasás/írás [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Visszatér:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```


Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a forma konverziójának vezérlését. Olvasás/írás [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


A képek tömörítési szintjét képviseli Olvasás/írás \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Visszatér:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


A képek tömörítési szintjét képviseli Olvasás/írás \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


Egy logikai jelző, amely azt jelzi, hogy a levágott részek a dokumentum részét képezik-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban lesznek szerializálva (ami esetleg nagyobb fájlt eredményez). Olvasás/írás boolean.

**Visszatér:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


Egy logikai jelző, amely azt jelzi, hogy a levágott részek a dokumentum részét képezik-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban lesznek szerializálva (ami esetleg nagyobb fájlt eredményez). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```


Meghatározza, hogy a szövegdoboz szerepel-e a renderelési területen vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: false.

**Visszatér:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```


Meghatározza, hogy a szövegdoboz szerepel-e a renderelési területen vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```


Meghatározza, hogy a forma megadott forgatása a renderelés során végrehajtásra kerül-e vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: true.

**Visszatér:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```


Meghatározza, hogy a forma megadott forgatása a renderelés során végrehajtásra kerül-e vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```


Meghatározza a külsőleg betöltött betűkészletek kezelésének módját. Olvasás/írás [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Visszatér:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```


Meghatározza a külsőleg betöltött betűkészletek kezelésének módját. Olvasás/írás [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Olyan opciókat biztosít, amelyek az exportált dokumentumban lévő Ink objektumok megjelenését szabályozzák. Csak olvasás [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatér:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


Megkap vagy beállít egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság false.

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


**Visszatér:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```


Megkap vagy beállít egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság false.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |