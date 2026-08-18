---
title: SVGOptions
second_title: Aspose.Slides Java API referencia
description: SVG beállításokat képvisel.
type: docs
url: /hu/com.aspose.slides/svgoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Az összes megvalósított interfész:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Egy SVG opciót képvisel.
## Constructors

| Konstruktor | Leírás |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Inicializál egy új SVGOptions osztálypéldányt. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Inicializál egy új SVGOptions osztálypéldányt, megadva a link beágyazási vezérlő objektumot. |
## Methods

| Metódus | Leírás |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
| [getUseFrameSize()](#getUseFrameSize--) | Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Meghatározza, hogy a megadott forgatást alkalmazza-e a forma renderelésekor vagy sem. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Meghatározza, hogy a megadott forgatást alkalmazza-e a forma renderelésekor vagy sem. |
| [getVectorizeText()](#getVectorizeText--) | Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Visszaadja vagy beállítja a metafájl rasterizálásának alacsonyabb felbontási határát. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Visszaadja vagy beállítja a metafájl rasterizálásának alacsonyabb felbontási határát. |
| [getDisable3DText()](#getDisable3DText--) | Meghatározza, hogy a 3D szöveg le legyen-e tiltva SVG-ben. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Meghatározza, hogy a 3D szöveg le legyen-e tiltva SVG-ben. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Letiltja a FromCornerX és FromCenter gradiens felosztását. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Letiltja a FromCornerX és FromCenter gradiens felosztását. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | Az SVG 1.1 nem támogatja a jelölők belső széleinak meghatározását. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | Az SVG 1.1 nem támogatja a jelölők belső széleinak meghatározását. |
| [getDefault()](#getDefault--) | Visszaadja az alapértelmezett beállításokat. |
| [getSimple()](#getSimple--) | Visszaadja a legegyszerűbb és legkisebb SVG fájl generálásához szükséges beállításokat. |
| [getWYSIWYG()](#getWYSIWYG--) | Visszaadja a legpontosabb SVG fájl generálásához szükséges beállításokat. |
| [getJpegQuality()](#getJpegQuality--) | Meghatározza a JPEG kódolás minőségét. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Meghatározza a JPEG kódolás minőségét. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Visszaadja és beállítja a visszahívási (callback) interfészt, amely lehetővé teszi a felhasználó számára a forma átalakításának vezérlését. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Visszaadja és beállítja a visszahívási (callback) interfészt, amely lehetővé teszi a felhasználó számára a forma átalakításának vezérlését. |
| [getPicturesCompression()](#getPicturesCompression--) | Kép tömörítési szintet képvisel |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Kép tömörítési szintet képvisel |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Egy logikai jelző, amely jelzi, hogy a vágott részek a dokumentum részét képezik-e. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Egy logikai jelző, amely jelzi, hogy a vágott részek a dokumentum részét képezik-e. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lekéri vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lekéri vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Inicializál egy új SVGOptions osztálypéldányt.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Inicializál egy új SVGOptions osztálypéldányt, megadva a link beágyazási vezérlő objektumot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | A link beágyazási vezérlő hivatkozása. |

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. **Csak olvasható** [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatér:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem. **Olvasás/írás**  boolean . Alapértelmezett érték hamis.

**Visszatér:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem. **Olvasás/írás**  boolean . Alapértelmezett érték hamis.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Meghatározza, hogy a megadott forgatást alkalmazza-e a forma renderelésekor vagy sem. **Olvasás/írás**  boolean . Alapértelmezett érték igaz.

**Visszatér:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Meghatározza, hogy a megadott forgatást alkalmazza-e a forma renderelésekor vagy sem. **Olvasás/írás**  boolean . Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. **Olvasás/írás** boolean.

**Visszatér:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Meghatározza, hogy a dián lévő szöveg grafikaként legyen-e mentve. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Visszaadja vagy beállítja a metafájl rasterizálásának alacsonyabb felbontási határát. **Olvasás/írás** int.

**Visszatér:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Visszaadja vagy beállítja a metafájl rasterizálásának alacsonyabb felbontási határát. **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Meghatározza, hogy a 3D szöveg le legyen-e tiltva SVG-ben. **Olvasás/írás** boolean.

**Visszatér:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Meghatározza, hogy a 3D szöveg le legyen-e tiltva SVG-ben. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Letiltja a FromCornerX és FromCenter gradiens felosztását. **Olvasás/írás** boolean.

**Visszatér:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Letiltja a FromCornerX és FromCenter gradiens felosztását. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 nem támogatja a jelölők belső széleinak meghatározását. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. **Olvasás/írás** boolean.

**Visszatér:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 nem támogatja a jelölők belső széleinak meghatározását. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Visszaadja az alapértelmezett beállításokat. **Csak olvasható** [SVGOptions](../../com.aspose.slides/svgoptions).

**Visszatér:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Visszaadja a legegyszerűbb és legkisebb SVG fájl generálásához szükséges beállításokat. **Csak olvasható** [SVGOptions](../../com.aspose.slides/svgoptions).

**Visszatér:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Visszaadja a legpontosabb SVG fájl generálásához szükséges beállításokat. **Csak olvasható** [SVGOptions](../../com.aspose.slides/svgoptions).

**Visszatér:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Meghatározza a JPEG kódolás minőségét. **Olvasás/írás** int.

**Visszatér:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Meghatározza a JPEG kódolás minőségét. **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Visszaadja és beállítja a visszahívási (callback) interfészt, amely lehetővé teszi a felhasználó számára a forma átalakításának vezérlését. **Olvasás/írás** [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Visszatér:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Visszaadja és beállítja a visszahívási (callback) interfészt, amely lehetővé teszi a felhasználó számára a forma átalakításának vezérlését. **Olvasás/írás** [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Kép tömörítési szintet képvisel

**Visszatér:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Kép tömörítési szintet képvisel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Egy logikai jelző, amely jelzi, hogy a vágott részek a dokumentum részét képezik-e. Ha true, a vágott részek eltávolításra kerülnek, ha false, akkor a dokumentumban maradnak (ami esetleg nagyobb fájlméretet eredményezhet).

**Visszatér:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Egy logikai jelző, amely jelzi, hogy a vágott részek a dokumentum részét képezik-e. Ha true, a vágott részek eltávolításra kerülnek, ha false, akkor a dokumentumban maradnak (ami esetleg nagyobb fájlméretet eredményezhet).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. **Olvasás/írás** [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Visszatér:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Meghatározza a külsőleg betöltött betűtípusok kezelésének módját. **Olvasás/írás** [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Lekéri vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság false-ra van állítva.

--------------------

> ```
> Példa:
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
public final void setDisableFontLigatures(boolean value)
```

Lekéri vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül legyen-e renderelve. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság false-ra van állítva.

--------------------

> ```
> Példa:
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