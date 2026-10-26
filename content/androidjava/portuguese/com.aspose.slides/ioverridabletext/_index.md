---
title: IOverridableText
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa texto substituível para um gráfico.
type: docs
url: /pt/com.aspose.slides/ioverridabletext/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Representa texto substituível para um gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Pode conter um texto formatado rico. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializa TextFrameForOverriding com o texto no parâmetro "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Pode conter um texto formatado rico. Se esta propriedade não for nula, então este valor de texto formatado substitui o texto gerado automaticamente. Texto gerado automaticamente é uma propriedade implícita do rótulo de dados, do rótulo da unidade de exibição do eixo de valores, do título do eixo, do título do gráfico, do rótulo da linha de tendência. Texto gerado automaticamente é formatado com a propriedade IFormattedTextContainer.TextFormat. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Inicializa TextFrameForOverriding com o texto no parâmetro "text". Se TextFrameForOverriding já estiver inicializado, então simplesmente altera seu texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto para um novo TextFrameForOverriding. |

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe) - Quadro de texto [ITextFrame](../../com.aspose.slides/itextframe)