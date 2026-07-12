---
title: ISVGOptions
second_title: Aspose.Slides Androidra a Java API hivatkozásával
description: SVG opciókat képviseli.
type: docs
url: /hu/com.aspose.slides/isvgoptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

SVG opciókat képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Meghatározza, hogy a dián lévő szöveget grafikai elemként mentse-e. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Meghatározza, hogy a dián lévő szöveget grafikai elemként mentse-e. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Visszaadja vagy beállítja a metafájl raszterizálásának alsó felbontási határát. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Visszaadja vagy beállítja a metafájl raszterizálásának alsó felbontási határát. |
| [getDisable3DText()](#getDisable3DText--) | Meghatározza, hogy a 3D szöveg le legyen-e tiltva az SVG-ben. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Meghatározza, hogy a 3D szöveg le legyen-e tiltva az SVG-ben. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Letiltja a FromCornerX és FromCenter gradientek felosztását. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Letiltja a FromCornerX és FromCenter gradientek felosztását. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | Az SVG 1.1 nem támogatja a jelölők belső margóinak definiálását. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | Az SVG 1.1 nem támogatja a jelölők belső margóinak definiálását. |
| [getJpegQuality()](#getJpegQuality--) | Meghatározza a JPEG kódolás minőségét. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Meghatározza a JPEG kódolás minőségét. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a forma átalakításának vezérlését. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a forma átalakításának vezérlését. |
| [getPicturesCompression()](#getPicturesCompression--) | A képek tömörítési szintjét képviseli Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | A képek tömörítési szintjét képviseli Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Egy boolean jelző, amely azt mutatja, hogy a levágott részek a dokumentum részei maradnak-e. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Egy boolean jelző, amely azt mutatja, hogy a levágott részek a dokumentum részei maradnak-e. |
| [getUseFrameSize()](#getUseFrameSize--) | Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Meghatározza, hogy a megadott forgást alkalmazza-e a forma renderelésekor. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Meghatározza, hogy a megadott forgást alkalmazza-e a forma renderelésekor. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Meghatározza a külsőleg betöltött betűkészletek kezelésének módját. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Meghatározza a külsőleg betöltött betűkészletek kezelésének módját. |
| [getInkOptions()](#getInkOptions--) | Olyan beállításokat biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lekéri vagy beállítja azt az értéket, amely jelzi, hogy a szöveget ligatúrák használata nélkül rendereli-e. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lekéri vagy beállítja azt az értéket, amely jelzi, hogy a szöveget ligatúrák használata nélkül rendereli-e. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Meghatározza, hogy a dián lévő szöveget grafikai elemként mentse-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Meghatározza, hogy a dián lévő szöveget grafikai elemként mentse-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Visszaadja vagy beállítja a metafájl raszterizálásának alsó felbontási határát. Olvasás/írás int.

**Visszatérési érték:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Visszaadja vagy beállítja a metafájl raszterizálásának alsó felbontási határát. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Meghatározza, hogy a 3D szöveg le legyen-e tiltva az SVG-ben. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Meghatározza, hogy a 3D szöveg le legyen-e tiltva az SVG-ben. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Letiltja a FromCornerX és FromCenter gradientek felosztását. Olvasás/írás boolean.

**Visszatérési érték:**
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

Az SVG 1.1 nem támogatja a jelölők belső margóinak definiálását. Az Aspose.Slides SVG írómotorja megoldást kínál erre: levágja a vonal végét a nyíllal, így a vonal nem fed le jelölőket. Ezzel a beállítással kikapcsolható ez a viselkedés. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

Az SVG 1.1 nem támogatja a jelölők belső margóinak definiálását. Az Aspose.Slides SVG írómotorja megoldást kínál erre: levágja a vonal végét a nyíllal, így a vonal nem fed le jelölőket. Ezzel a beállítással kikapcsolható ez a viselkedés. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Meghatározza a JPEG kódolás minőségét. Olvasás/írás int.

**Visszatérési érték:**
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

Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a forma átalakításának vezérlését. Olvasás/írás [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Visszatérési érték:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Visszaadja és beállítja a visszahívási interfészt, amely lehetővé teszi a felhasználó számára a forma átalakításának vezérlését. Olvasás/írás [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

A képek tömörítési szintjét képviseli Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Visszatérési érték:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

A képek tömörítési szintjét képviseli Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Egy boolean jelző, amely azt mutatja, hogy a levágott részek a dokumentum részei maradnak-e. Ha true, a levágott részek eltávolításra kerülnek, ha false, akkor a dokumentumban maradnak (ami esetleg nagyobb fájlt eredményezhet). Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Egy boolean jelző, amely azt mutatja, hogy a levágott részek a dokumentum részei maradnak-e. Ha true, a levágott részek eltávolításra kerülnek, ha false, akkor a dokumentumban maradnak (ami esetleg nagyobb fájlt eredményezhet). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: false.

**Visszatérési érték:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Meghatározza, hogy a szövegkeret szerepel-e a renderelési területen vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Meghatározza, hogy a forma megadott forgását alkalmazza-e a renderelés során vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Meghatározza, hogy a forma megadott forgását alkalmazza-e a renderelés során vagy sem. Olvasás/írás  boolean . Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Meghatározza a külsőleg betöltött betűkészletek kezelésének módját. Olvasás/írás [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Visszatérési érték:**
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

Olyan beállításokat biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatérési érték:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Lekéri vagy beállítja azt az értéket, amely jelzi, hogy a szöveget ligatúrák használata nélkül rendereli-e. Ha true, a ligatúrák le lesznek tiltva a kimenetben. Alapértelmezés szerint ez a tulajdonság false.

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


**Visszatérési érték:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Lekéri vagy beállítja azt az értéket, amely jelzi, hogy a szöveget ligatúrák használata nélkül rendereli-e. Ha true, a ligatúrák le lesznek tiltva a kimenetben. Alapértelmezés szerint ez a tulajdonság false.

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