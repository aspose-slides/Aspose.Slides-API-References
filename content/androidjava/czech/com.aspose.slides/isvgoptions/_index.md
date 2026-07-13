---
title: ISVGOptions
second_title: Aspose.Slides pro Android přes referenci Java API
description: Představuje možnosti SVG.
type: docs
url: /cs/com.aspose.slides/isvgoptions/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Představuje možnosti SVG.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Určuje, zda bude text na snímku uložen jako grafika. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Určuje, zda bude text na snímku uložen jako grafika. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Vrací nebo nastavuje limit nižšího rozlišení pro rasterizaci metafilu. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Vrací nebo nastavuje limit nižšího rozlišení pro rasterizaci metafilu. |
| [getDisable3DText()](#getDisable3DText--) | Určuje, zda je 3D text v SVG zakázán. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Určuje, zda je 3D text v SVG zakázán. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Zakazuje rozdělení gradientů FromCornerX a FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Zakazuje rozdělení gradientů FromCornerX a FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 postrádá možnost definovat odsazení pro značky. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 postrádá možnost definovat odsazení pro značky. |
| [getJpegQuality()](#getJpegQuality--) | Určuje kvalitu kódování JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Určuje kvalitu kódování JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvarů. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvarů. |
| [getPicturesCompression()](#getPicturesCompression--) | Představuje úroveň komprese obrázků. Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Představuje úroveň komprese obrázků. Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Příznak typu boolean, který určuje, zda oříznuté části zůstávají součástí dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Příznak typu boolean, který určuje, zda oříznuté části zůstávají součástí dokumentu. |
| [getUseFrameSize()](#getUseFrameSize--) | Určuje, zda bude textový rámeček zahrnut do vykreslovací oblasti. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Určuje, zda bude textový rámeček zahrnut do vykreslovací oblasti. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Určuje, zda se při vykreslování provede určená rotace tvaru. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Určuje, zda se při vykreslování provede určená rotace tvaru. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Určuje způsob zacházení s externě načtenými písmy. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Určuje způsob zacházení s externě načtenými písmy. |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Získává nebo nastavuje hodnotu určující, zda je text vykreslován bez ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Získává nebo nastavuje hodnotu určující, zda je text vykreslován bez ligatur. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```


Určuje, zda bude text na snímku uložen jako grafika. Read/write boolean.

**Vrací:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```


Určuje, zda bude text na snímku uložen jako grafika. Read/write boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```


Vrací nebo nastavuje limit nižšího rozlišení pro rasterizaci metafilu. Read/write int.

**Vrací:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```


Vrací nebo nastavuje limit nižšího rozlišení pro rasterizaci metafilu. Read/write int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```


Určuje, zda je 3D text v SVG zakázán. Read/write boolean.

**Vrací:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```


Určuje, zda je 3D text v SVG zakázán. Read/write boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```


Zakazuje rozdělení gradientů FromCornerX a FromCenter. Read/write boolean.

**Vrací:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```


Zakazuje rozdělení gradientů FromCornerX a FromCenter. Read/write boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```


SVG 1.1 postrádá možnost definovat odsazení pro značky. SVG engine Aspose.Slides má pro tento problém řešení: ořízne konce čar s šipkami, takže čára nepřekrývá značky. Tato možnost vypíná takové chování. Read/write boolean.

**Vrací:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```


SVG 1.1 postrádá možnost definovat odsazení pro značky. SVG engine Aspose.Slides má pro tento problém řešení: ořízne konce čar s šipkami, takže čára nepřekrývá značky. Tato možnost vypíná takové chování. Read/write boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```


Určuje kvalitu kódování JPEG. Read/write int.

**Vrací:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```


Určuje kvalitu kódování JPEG. Read/write int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```


Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvarů. Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Vrací:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```


Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvarů. Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


Představuje úroveň komprese obrázků. Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Vrací:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


Představuje úroveň komprese obrázků. Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


Příznak typu boolean, který určuje, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru). Read/write boolean.

**Vrací:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


Příznak typu boolean, který určuje, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru). Read/write boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```


Určuje, zda bude textový rámeček zahrnut do vykreslovací oblasti. Read/write  boolean . Výchozí hodnota je false.

**Vrací:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```


Určuje, zda bude textový rámeček zahrnut do vykreslovací oblasti. Read/write  boolean . Výchozí hodnota je false.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```


Určuje, zda se při vykreslování provede určená rotace tvaru. Read/write  boolean . Výchozí hodnota je true.

**Vrací:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```


Určuje, zda se při vykreslování provede určená rotace tvaru. Read/write  boolean . Výchozí hodnota je true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```


Určuje způsob zacházení s externě načtenými písmy. Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Vrací:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```


Určuje způsob zacházení s externě načtenými písmy. Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Vrací:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


Získává nebo nastavuje hodnotu určující, zda je text vykreslován bez ligatur. Když je nastaveno na true, ligatury budou vygenerovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost false.

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

**Vrací:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```


Získává nebo nastavuje hodnotu určující, zda je text vykreslován bez ligatur. Když je nastaveno na true, ligatury budou vygenerovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost false.

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

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |