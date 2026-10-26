---
title: HtmlFormatter
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa um modelo de arquivo HTML.
type: docs
url: /pt/com.aspose.slides/htmlformatter/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Representa um modelo de arquivo HTML.
## Métodos

| Método | Descrição |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Cria e retorna um formatador HTML para uma visualização de documento simples que consiste em sequências de slides um abaixo do outro. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Cria e retorna um formatador HTML para um slide show HTML simples que exibe os slides um após o outro. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Cria e retorna um formatador HTML para geração de HTML personalizada baseada em callbacks. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Cria e retorna um formatador HTML para uma visualização de documento simples que consiste em sequências de slides um abaixo do outro.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| css | java.lang.String | Especifica o CSS para este arquivo. |
| showSlideTitle | boolean | Adiciona o título do slide se houver um acima da imagem do slide. |

**Retorno:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - O objeto [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Cria e retorna um formatador HTML para um slide show HTML simples que exibe os slides um após o outro.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| css | java.lang.String | Especifica a URL do arquivo CSS usado. |
| showSlideTitle | boolean | Adiciona o título do slide se houver um acima da imagem do slide. |

**Retorno:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - O objeto [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Cria e retorna um formatador HTML para geração de HTML personalizada baseada em callbacks.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Interface de callback que controla a geração do arquivo HTML. |

**Retorno:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - O objeto [HtmlFormatter](../../com.aspose.slides/htmlformatter).