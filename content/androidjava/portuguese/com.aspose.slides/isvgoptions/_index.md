---
title: ISVGOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções SVG.
type: docs
url: /pt/com.aspose.slides/isvgoptions/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Representa opções SVG.
## Métodos

| Method | Description |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Determina se o texto em um slide será salvo como gráfico. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Determina se o texto em um slide será salvo como gráfico. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Retorna ou define o limite inferior de resolução para rasterização de metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Retorna ou define o limite inferior de resolução para rasterização de metafile. |
| [getDisable3DText()](#getDisable3DText--) | Determina se o texto 3D está desativado em SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Determina se o texto 3D está desativado em SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Desativa a divisão dos gradientes FromCornerX e FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Desativa a divisão dos gradientes FromCornerX e FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 não tem capacidade de definir recuos para marcadores. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 não tem capacidade de definir recuos para marcadores. |
| [getJpegQuality()](#getJpegQuality--) | Determina a qualidade de codificação JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Determina a qualidade de codificação JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Retorna e define uma interface de callback que permite ao usuário controlar a conversão de shape. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Retorna e define uma interface de callback que permite ao usuário controlar a conversão de shape. |
| [getPicturesCompression()](#getPicturesCompression--) | Representa o nível de compressão de pictures. Leitura/gravação \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representa o nível de compressão de pictures. Leitura/gravação \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. |
| [getUseFrameSize()](#getUseFrameSize--) | Determina se a caixa de texto será incluída em uma área de renderização ou não. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Determina se a caixa de texto será incluída em uma área de renderização ou não. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Determina se a rotação especificada da shape será executada ao renderizar ou não. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Determina se a rotação especificada da shape será executada ao renderizar ou não. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Determina um método de tratamento de fontes carregadas externamente. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Determina um método de tratamento de fontes carregadas externamente. |
| [getInkOptions()](#getInkOptions--) | Fornece opções que controlam a aparência de objetos Ink no documento exportado. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtém ou define um valor indicando se o texto é renderizado sem usar ligaduras. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtém ou define um valor indicando se o texto é renderizado sem usar ligaduras. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Determina se o texto em um slide será salvo como gráfico. Leitura/gravação booleano.

**Retorna:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Determina se o texto em um slide será salvo como gráfico. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Retorna ou define o limite inferior de resolução para rasterização de metafile. Leitura/gravação int.

**Retorna:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Retorna ou define o limite inferior de resolução para rasterização de metafile. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Determina se o texto 3D está desativado em SVG. Leitura/gravação booleano.

**Retorna:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Determina se o texto 3D está desativado em SVG. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Desativa a divisão dos gradientes FromCornerX e FromCenter. Leitura/gravação booleano.

**Retorna:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Desativa a divisão dos gradientes FromCornerX e FromCenter. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 não tem capacidade de definir recuos para marcadores. O mecanismo de gravação SVG da Aspose.Slides tem uma solução alternativa para esse problema: ele recorta a ponta da linha com seta, de modo que a linha não sobreponha os marcadores. Esta opção desativa esse comportamento. Leitura/gravação booleano.

**Retorna:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 não tem capacidade de definir recuos para marcadores. O mecanismo de gravação SVG da Aspose.Slides tem uma solução alternativa para esse problema: ele recorta a ponta da linha com seta, de modo que a linha não sobreponha os marcadores. Esta opção desativa esse comportamento. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Determina a qualidade de codificação JPEG. Leitura/gravação int.

**Retorna:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Determina a qualidade de codificação JPEG. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Retorna e define uma interface de callback que permite ao usuário controlar a conversão de shape. Leitura/gravação [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Retorna:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Retorna e define uma interface de callback que permite ao usuário controlar a conversão de shape. Leitura/gravação [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Representa o nível de compressão de pictures. Leitura/gravação \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Retorna:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Representa o nível de compressão de pictures. Leitura/gravação \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se true, as partes recortadas serão removidas; se false, serão serializadas no documento (o que pode levar a um arquivo maior). Leitura/gravação booleano.

**Retorna:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se true, as partes recortadas serão removidas; se false, serão serializadas no documento (o que pode levar a um arquivo maior). Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Determina se a caixa de texto será incluída em uma área de renderização ou não. Leitura/gravação boolean. Valor padrão é false.

**Retorna:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Determina se a caixa de texto será incluída em uma área de renderização ou não. Leitura/gravação boolean. Valor padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Determina se a rotação especificada da shape será executada ao renderizar ou não. Leitura/gravação boolean. Valor padrão é true.

**Retorna:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Determina se a rotação especificada da shape será executada ao renderizar ou não. Leitura/gravação boolean. Valor padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Determina um método de tratamento de fontes carregadas externamente. Leitura/gravação [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Retorna:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Determina um método de tratamento de fontes carregadas externamente. Leitura/gravação [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Fornece opções que controlam a aparência de objetos Ink no documento exportado. Somente leitura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retorna:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Obtém ou define um valor indicando se o texto é renderizado sem usar ligaduras. Quando definido como true, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como false.

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

**Retorna:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Obtém ou define um valor indicando se o texto é renderizado sem usar ligaduras. Quando definido como true, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como false.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |