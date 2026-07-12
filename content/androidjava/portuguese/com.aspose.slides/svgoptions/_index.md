---
title: SVGOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções de SVG.
type: docs
url: /pt/com.aspose.slides/svgoptions/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Representa opções de SVG.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Inicializa uma nova instância da classe SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Inicializa uma nova instância da classe SVGOptions especificando o objeto controlador de incorporação de links. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado. |
| [getUseFrameSize()](#getUseFrameSize--) | Determina se a moldura de texto será incluída em uma área de renderização ou não. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Determina se a moldura de texto será incluída em uma área de renderização ou não. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Determina se a rotação especificada da forma deve ser executada ao renderizar ou não. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Determina se a rotação especificada da forma deve ser executada ao renderizar ou não. |
| [getVectorizeText()](#getVectorizeText--) | Determina se o texto em um slide será salvo como gráficos. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Determina se o texto em um slide será salvo como gráficos. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Retorna ou define o limite inferior de resolução para rasterização de metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Retorna ou define o limite inferior de resolução para rasterização de metafile. |
| [getDisable3DText()](#getDisable3DText--) | Determina se o texto 3D está desativado em SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Determina se o texto 3D está desativado em SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Desativa a divisão de gradientes FromCornerX e FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Desativa a divisão de gradientes FromCornerX e FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | O SVG 1.1 não possui capacidade de definir recuos para marcadores. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | O SVG 1.1 não possui capacidade de definir recuos para marcadores. |
| [getDefault()](#getDefault--) | Retorna as configurações padrão. |
| [getSimple()](#getSimple--) | Retorna configurações para a geração do arquivo SVG mais simples e pequeno. |
| [getWYSIWYG()](#getWYSIWYG--) | Retorna configurações para a geração do arquivo SVG mais precisa. |
| [getJpegQuality()](#getJpegQuality--) | Determina a qualidade de codificação JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Determina a qualidade de codificação JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Retorna e define uma interface de retorno de chamada que permite ao usuário controlar a conversão de formas. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Retorna e define uma interface de retorno de chamada que permite ao usuário controlar a conversão de formas. |
| [getPicturesCompression()](#getPicturesCompression--) | Representa o nível de compressão das imagens |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representa o nível de compressão das imagens |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Determina uma forma de tratar fontes carregadas externamente. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Determina uma forma de tratar fontes carregadas externamente. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaturas. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaturas. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```


Inicializa uma nova instância da classe SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```


Inicializa uma nova instância da classe SVGOptions especificando o objeto controlador de incorporação de links.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | A referência do controlador de incorporação de links. |

--------------------

O controlador de incorporação de links é um objeto delegado responsável por decidir se recursos (como imagens) precisam ser incorporados ou referenciados como recursos externos. |
### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Fornece opções que controlam a aparência dos objetos Ink no documento exportado. Somente leitura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retorna:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```


Determina se a moldura de texto será incluída em uma área de renderização ou não. Leitura/Gravação  boolean . Valor padrão é false.

**Retorna:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```


Determina se a moldura de texto será incluída em uma área de renderização ou não. Leitura/Gravação  boolean . Valor padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```


Determina se a rotação especificada da forma deve ser executada ao renderizar ou não. Leitura/Gravação  boolean . Valor padrão é true.

**Retorna:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```


Determina se a rotação especificada da forma deve ser executada ao renderizar ou não. Leitura/Gravação  boolean . Valor padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```


Determina se o texto em um slide será salvo como gráficos. Leitura/Gravação boolean.

**Retorna:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```


Determina se o texto em um slide será salvo como gráficos. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```


Retorna ou define o limite inferior de resolução para rasterização de metafile. Leitura/Gravação int.

**Retorna:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```


Retorna ou define o limite inferior de resolução para rasterização de metafile. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```


Determina se o texto 3D está desativado em SVG. Leitura/Gravação boolean.

**Retorna:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```


Determina se o texto 3D está desativado em SVG. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```


Desativa a divisão de gradientes FromCornerX e FromCenter. Leitura/Gravação boolean.

**Retorna:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```


Desativa a divisão de gradientes FromCornerX e FromCenter. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```


O SVG 1.1 não possui capacidade de definir recuos para marcadores. Aspose.Slides SVG writing engine tem solução alternativa para esse problema: ele recorta a extremidade da linha com seta, de modo que a linha não se sobreponha aos marcadores. Esta opção desativa esse comportamento. Leitura/Gravação boolean.

**Retorna:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```


O SVG 1.1 não possui capacidade de definir recuos para marcadores. Aspose.Slides SVG writing engine tem solução alternativa para esse problema: ele recorta a extremidade da linha com seta, de modo que a linha não se sobreponha aos marcadores. Esta opção desativa esse comportamento. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```


Retorna as configurações padrão. Somente leitura [SVGOptions](../../com.aspose.slides/svgoptions).

**Retorna:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```


Retorna configurações para a geração do arquivo SVG mais simples e pequeno. Somente leitura [SVGOptions](../../com.aspose.slides/svgoptions).

**Retorna:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```


Retorna configurações para a geração do arquivo SVG mais precisa. Somente leitura [SVGOptions](../../com.aspose.slides/svgoptions).

**Retorna:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Determina a qualidade de codificação JPEG. Leitura/Gravação int.

**Retorna:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Determina a qualidade de codificação JPEG. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```


Retorna e define uma interface de retorno de chamada que permite ao usuário controlar a conversão de formas. Leitura/Gravação [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Retorna:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```


Retorna e define uma interface de retorno de chamada que permite ao usuário controlar a conversão de formas. Leitura/Gravação [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```


Representa o nível de compressão das imagens

**Retorna:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


Representa o nível de compressão das imagens

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```


Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se true, as partes recortadas serão removidas; se false, elas serão serializadas no documento (o que pode levar a um arquivo maior)

**Retorna:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```


Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se true, as partes recortadas serão removidas; se false, elas serão serializadas no documento (o que pode levar a um arquivo maior)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```


Determina uma forma de tratar fontes carregadas externamente. Leitura/Gravação [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Retorna:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```


Determina uma forma de tratar fontes carregadas externamente. Leitura/Gravação [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Obtém ou define um valor que indica se o texto é renderizado sem usar ligaturas. Quando definido como true, as ligaturas serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como false.

--------------------

> ```
> Exemplo:
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
public final void setDisableFontLigatures(boolean value)
```


Obtém ou define um valor que indica se o texto é renderizado sem usar ligaturas. Quando definido como true, as ligaturas serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como false.

--------------------

> ```
> Exemplo:
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