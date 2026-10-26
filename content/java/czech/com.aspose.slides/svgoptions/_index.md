---
title: SVGOptions
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje možnosti SVG.
type: docs
url: /cs/com.aspose.slides/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Reprezentuje možnosti SVG.

## Konstruktory

| Constructor | Description |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Inicializuje novou instanci třídy SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Inicializuje novou instanci třídy SVGOptions s určeným objektem řadiče vkládání odkazů. |

## Metody

| Method | Description |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. |
| [getUseFrameSize()](#getUseFrameSize--) | Určuje, zda bude textový rámec zahrnut v oblasti vykreslování, nebo ne. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Určuje, zda bude textový rámec zahrnut v oblasti vykreslování, nebo ne. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Určuje, zda se při vykreslování provede určená rotace tvaru, nebo ne. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Určuje, zda se při vykreslování provede určená rotace tvaru, nebo ne. |
| [getVectorizeText()](#getVectorizeText--) | Určuje, zda bude text na snímku uložen jako grafika. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Určuje, zda bude text na snímku uložen jako grafika. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Vrací nebo nastavuje dolní limit rozlišení pro rastrování metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Vrací nebo nastavuje dolní limit rozlišení pro rastrování metafile. |
| [getDisable3DText()](#getDisable3DText--) | Určuje, zda je 3D text v SVG zakázán. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Určuje, zda je 3D text v SVG zakázán. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Zakazuje rozdělení gradientů FromCornerX a FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Zakazuje rozdělení gradientů FromCornerX a FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 postrádá možnost definovat vnitřní okraje pro značky. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 postrádá možnost definovat vnitřní okraje pro značky. |
| [getDefault()](#getDefault--) | Vrací výchozí nastavení. |
| [getSimple()](#getSimple--) | Vrací nastavení pro nejjednodušší a nejmenší generování souboru SVG. |
| [getWYSIWYG()](#getWYSIWYG--) | Vrací nastavení pro nejpřesnější generování souboru SVG. |
| [getJpegQuality()](#getJpegQuality--) | Určuje kvalitu kódování JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Určuje kvalitu kódování JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. |
| [getPicturesCompression()](#getPicturesCompression--) | Reprezentuje úroveň komprese obrázků |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Reprezentuje úroveň komprese obrázků |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Logická příznaková hodnota udává, zda oříznuté části zůstávají jako součást dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Logická příznaková hodnota udává, zda oříznuté části zůstávají jako součást dokumentu. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Určuje způsob zacházení s externě načtenými fonty. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Určuje způsob zacházení s externě načtenými fonty. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Vrací nebo nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Vrací nebo nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Inicializuje novou instanci třídy SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Inicializuje novou instanci třídy SVGOptions s určeným objektem řadiče vkládání odkazů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Odkaz na řadič vkládání odkazů.

--------------------

Link embedding controller je delegátní objekt, který je zodpovědný za rozhodování, zda mají být zdroje (například obrázky) vloženy nebo odkazovány jako externí zdroje. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. Pouze pro čtení [IInkOptions](../../com.aspose.slides/iinkoptions)

**Vrací:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Určuje, zda bude textový rámec zahrnut v oblasti vykreslování, nebo ne. Čtení/zápis  boolean . Výchozí hodnota je false.

**Vrací:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Určuje, zda bude textový rámec zahrnut v oblasti vykreslování, nebo ne. Čtení/zápis  boolean . Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Určuje, zda se při vykreslování provede určená rotace tvaru, nebo ne. Čtení/zápis  boolean . Výchozí hodnota je true.

**Vrací:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Určuje, zda se při vykreslování provede určená rotace tvaru, nebo ne. Čtení/zápis  boolean . Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Určuje, zda bude text na snímku uložen jako grafika. Čtení/zápis boolean.

**Vrací:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Určuje, zda bude text na snímku uložen jako grafika. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Vrací nebo nastavuje dolní limit rozlišení pro rastrování metafile. Čtení/zápis int.

**Vrací:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Vrací nebo nastavuje dolní limit rozlišení pro rastrování metafile. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Určuje, zda je 3D text v SVG zakázán. Čtení/zápis boolean.

**Vrací:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Určuje, zda je 3D text v SVG zakázán. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Zakazuje rozdělení gradientů FromCornerX a FromCenter. Čtení/zápis boolean.

**Vrací:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Zakazuje rozdělení gradientů FromCornerX a FromCenter. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 postrádá možnost definovat vnitřní okraje pro značky. Engine pro zápis SVG v Aspose.Slides má pro tento problém řešení: ořízne konec čáry s šipkou, takže čára nepřekrývá značky. Toto nastavení tuto funkci vypne. Čtení/zápis boolean.

**Vrací:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 postrádá možnost definovat vnitřní okraje pro značky. Engine pro zápis SVG v Aspose.Slides má pro tento problém řešení: ořízne konec čáry s šipkou, takže čára nepřekrývá značky. Toto nastavení tuto funkci vypne. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Vrací výchozí nastavení. Pouze pro čtení [SVGOptions](../../com.aspose.slides/svgoptions).

**Vrací:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Vrací nastavení pro nejjednodušší a nejmenší generování souboru SVG. Pouze pro čtení [SVGOptions](../../com.aspose.slides/svgoptions).

**Vrací:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Vrací nastavení pro nejpřesnější generování souboru SVG. Pouze pro čtení [SVGOptions](../../com.aspose.slides/svgoptions).

**Vrací:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Určuje kvalitu kódování JPEG. Čtení/zápis int.

**Vrací:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Určuje kvalitu kódování JPEG. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. Čtení/zápis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Vrací:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. Čtení/zápis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Reprezentuje úroveň komprese obrázků

**Vrací:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Reprezentuje úroveň komprese obrázků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Logická příznaková hodnota udává, zda oříznuté části zůstávají jako součást dokumentu. Pokud je true, oříznuté části budou odstraněny; pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru)

**Vrací:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Logická příznaková hodnota udává, zda oříznuté části zůstávají jako součást dokumentu. Pokud je true, oříznuté části budou odstraněny; pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Určuje způsob zacházení s externě načtenými fonty. Čtení/zápis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Vrací:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Určuje způsob zacházení s externě načtenými fonty. Čtení/zápis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Vrací nebo nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastavena na true, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost false.

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
public final void setDisableFontLigatures(boolean value)
```

Vrací nebo nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastavena na true, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost false.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |