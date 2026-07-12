---
title: EmbedAllFontsHtmlController
second_title: Referência da API Java do Aspose.Slides para Android
description: Classe controladora de formatação a ser usada para incorporar todas as fontes da apresentação no formato WOFF.
type: docs
url: /pt/com.aspose.slides/embedallfontshtmlcontroller/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

A classe controladora de formatação a ser usada para incorporar todas as fontes da apresentação no formato WOFF.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Cria uma nova instância |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Cria uma nova instância |
## Métodos

| Método | Descrição |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Chamado para escrever o cabeçalho do documento html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Chamado para escrever o rodapé do documento html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Chamado para escrever o cabeçalho do slide html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Chamado para escrever o rodapé do slide html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Chamado antes da renderização da forma. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Chamado antes da renderização da forma. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Grava todas as fontes contidas em [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Grava os dados como base64 dentro do próprio documento HTML |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


Cria uma nova instância

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


Cria uma nova instância

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Fontes a serem excluídas da incorporação |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Chamado para escrever o cabeçalho do documento html. Chamado uma vez por conversão de apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação que está sendo renderizada no momento. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Chamado para escrever o rodapé do documento html. Chamado uma vez por conversão de apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação que está sendo renderizada no momento. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Chamado para escrever o cabeçalho do slide html. Chamado uma vez para cada slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide que está sendo renderizado no momento. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Chamado para escrever o rodapé do slide html. Chamado uma vez para cada slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide que está sendo renderizado no momento. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será finalizada, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma que está prestes a ser renderizada. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será finalizada, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma que foi renderizada por último. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


Grava todas as fontes contidas em [Presentation](../../com.aspose.slides/presentation).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação que está sendo renderizada no momento. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


Grava os dados como base64 dentro do próprio documento HTML

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Gerador HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte a ser serializada |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte substituída (se a substituição de fonte ocorreu), null caso contrário |
| fontStyle | java.lang.String | Estilo da fonte |
| fontWeight | java.lang.String | Espessura da fonte |
| fontData | byte[] | Dados da fonte |