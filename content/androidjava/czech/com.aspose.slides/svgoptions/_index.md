---
title: SVGOptions
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje nastavení SVG.
type: docs
url: /cs/com.aspose.slides/svgoptions/
---
**Dědění:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Všechny implementované rozhraní:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Představuje nastavení SVG.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Inicializuje novou instanci třídy SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Inicializuje novou instanci třídy SVGOptions s určením objektu řadiče vkládání odkazů. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. |
| [getUseFrameSize()](#getUseFrameSize--) | Určuje, zda bude textový rámeček zahrnut v oblasti vykreslování, nebo ne. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Určuje, zda bude textový rámeček zahrnut v oblasti vykreslování, nebo ne. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Určuje, zda při vykreslování provést zadanou rotaci tvaru, nebo ne. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Určuje, zda při vykreslování provést zadanou rotaci tvaru, nebo ne. |
| [getVectorizeText()](#getVectorizeText--) | Určuje, zda bude text na snímku uložen jako grafika. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Určuje, zda bude text na snímku uložen jako grafika. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Vrací nebo nastavuje spodní hranici rozlišení pro rasterizaci metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Vrací nebo nastavuje spodní hranici rozlišení pro rasterizaci metafile. |
| [getDisable3DText()](#getDisable3DText--) | Určuje, zda je 3D text v SVG zakázán. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Určuje, zda je 3D text v SVG zakázán. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Zakazuje rozdělování gradientů FromCornerX a FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Zakazuje rozdělování gradientů FromCornerX a FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 postrádá možnost definovat odsazení pro značky. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 postrádá možnost definovat odsazení pro značky. |
| [getDefault()](#getDefault--) | Vrací výchozí nastavení. |
| [getSimple()](#getSimple--) | Vrací nastavení pro nejjednodušší a nejmenší generování SVG souboru. |
| [getWYSIWYG()](#getWYSIWYG--) | Vrací nastavení pro nejpřesnější generování SVG souboru. |
| [getJpegQuality()](#getJpegQuality--) | Určuje kvalitu kódování JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Určuje kvalitu kódování JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. |
| [getPicturesCompression()](#getPicturesCompression--) | Reprezentuje úroveň komprese obrázků |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Reprezentuje úroveň komprese obrázků |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Příznak typu boolean udává, zda oříznuté části zůstávají součástí dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Příznak typu boolean udává, zda oříznuté části zůstávají součástí dokumentu. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Určuje způsob zacházení s externě načtenými fonty. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Určuje způsob zacházení s externě načtenými fonty. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Načte nebo nastaví hodnotu udávající, zda je text vykreslován bez ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Načte nebo nastaví hodnotu udávající, zda je text vykreslován bez ligatur. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Inicializuje novou instanci třídy SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Inicializuje novou instanci třídy SVGOptions s určením objektu řadiče vkládání odkazů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Reference na řadič vkládání odkazů. |

--------------------

Řadič vkládání odkazů je delegátní objekt, který je zodpovědný za rozhodování, zda mají být zdroje (například obrázky) vloženy nebo referencovány jako externí zdroje. |
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

Určuje, zda bude textový rámeček zahrnut v oblasti vykreslování, nebo ne. Čtení/Zápis  boolean . Výchozí hodnota je false.

**Vrací:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Určuje, zda bude textový rámeček zahrnut v oblasti vykreslování, nebo ne. Čtení/Zápis  boolean . Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Určuje, zda při vykreslování provést zadanou rotaci tvaru, nebo ne. Čtení/Zápis  boolean . Výchozí hodnota je true.

**Vrací:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Určuje, zda při vykreslování provést zadanou rotaci tvaru, nebo ne. Čtení/Zápis  boolean . Výchozí hodnota je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Určuje, zda bude text na snímku uložen jako grafika. Čtení/Zápis boolean.

**Vrací:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Určuje, zda bude text na snímku uložen jako grafika. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Vrací nebo nastavuje spodní hranici rozlišení pro rasterizaci metafile. Čtení/Zápis int.

**Vrací:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Vrací nebo nastavuje spodní hranici rozlišení pro rasterizaci metafile. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Určuje, zda je 3D text v SVG zakázán. Čtení/Zápis boolean.

**Vrací:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Určuje, zda je 3D text v SVG zakázán. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Zakazuje rozdělování gradientů FromCornerX a FromCenter. Čtení/Zápis boolean.

**Vrací:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Zakazuje rozdělování gradientů FromCornerX a FromCenter. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 postrádá možnost definovat odsazení pro značky. Aspose.Slides SVG writing engine má řešení tohoto problému: ořezává konec čáry s šipkou, takže čára nepřekrývá značky. Tato možnost vypíná takové chování. Čtení/Zápis boolean.

**Vrací:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 postrádá možnost definovat odsazení pro značky. Aspose.Slides SVG writing engine má řešení tohoto problému: ořezává konec čáry s šipkou, takže čára nepřekrývá značky. Tato možnost vypíná takové chování. Čtení/Zápis boolean.

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

Vrací nastavení pro nejjednodušší a nejmenší generování SVG souboru. Pouze pro čtení [SVGOptions](../../com.aspose.slides/svgoptions).

**Vrací:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Vrací nastavení pro nejpřesnější generování SVG souboru. Pouze pro čtení [SVGOptions](../../com.aspose.slides/svgoptions).

**Vrací:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Určuje kvalitu kódování JPEG. Čtení/Zápis int.

**Vrací:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Určuje kvalitu kódování JPEG. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. Čtení/Zápis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Vrací:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. Čtení/Zápis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

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

Příznak typu boolean udává, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru).

**Vrací:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Příznak typu boolean udává, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Určuje způsob zacházení s externě načtenými fonty. Čtení/Zápis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Vrací:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Určuje způsob zacházení s externě načtenými fonty. Čtení/Zápis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Načte nebo nastaví hodnotu udávající, zda je text vykreslován bez ligatur. Když je nastaveno na true, ligatury budou v renderovaném výstupu zakázány. Implicitně je tato vlastnost nastavena na false.

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

Načte nebo nastaví hodnotu udávající, zda je text vykreslován bez ligatur. Když je nastaveno na true, ligatury budou v renderovaném výstupu zakázány. Implicitně je tato vlastnost nastavena na false.

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