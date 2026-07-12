---
title: ITextFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um TextFrame.
type: docs
url: /pt/com.aspose.slides/itextframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Representa um TextFrame.
## Métodos

| Método | Descrição |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Retorna a lista de todos os parágrafos em um quadro. |
| [getText()](#getText--) | Obtém ou define o texto simples para um TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Obtém ou define o texto simples para um TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Retorna o objeto de formatação para este objeto TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornece acesso fácil a hyperlinks contidos. |
| [getParentShape()](#getParentShape--) | Retorna a forma pai ou null se o objeto pai não implementar a interface IShape Somente leitura [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Retorna a célula pai ou null se o objeto pai não implementar a interface ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une execuções com a mesma formatação em todos os parágrafos. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [splitTextByColumns()](#splitTextByColumns--) | Divide o conteúdo de texto do [ITextFrame](../../com.aspose.slides/itextframe) em um array de strings, onde cada elemento corresponde a uma coluna de texto separada dentro do quadro. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Realça todas as correspondências da expressão regular com a cor especificada. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Realça todas as correspondências da expressão regular com a cor especificada. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Substitui todas as ocorrências do texto especificado por outro texto especificado. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Substitui todas as correspondências da expressão regular pela string especificada. |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```


Retorna a lista de todos os parágrafos em um quadro. Somente leitura [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Retorno:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```


Obtém ou define o texto simples para um TextFrame. Leitura/Gravação String.

Valor: O texto.

**Retorno:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Obtém ou define o texto simples para um TextFrame. Leitura/Gravação String.

Valor: O texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```


Retorna o objeto de formatação para este objeto TextFrame. Somente leitura [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Retorno:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Fornece acesso fácil a hyperlinks contidos. Somente leitura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retorno:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```


Retorna a forma pai ou null se o objeto pai não implementar a interface IShape Somente leitura [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Estas asserções são sempre verdadeiras
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retorno:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```


Retorna a célula pai ou null se o objeto pai não implementar a interface ICell. Somente leitura [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Estas asserções são sempre verdadeiras
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retorno:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Une execuções com a mesma formatação em todos os parágrafos.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```


Realça todas as correspondências do texto de exemplo com a cor especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | O texto a ser realçado. |
| highlightColor | java.lang.Integer | A cor para realçar o texto. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```


Divide o conteúdo de texto do [ITextFrame](../../com.aspose.slides/itextframe) em um array de strings, onde cada elemento corresponde a uma coluna de texto separada dentro do quadro.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Obtenha a primeira forma no slide e faça cast para ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Divida o conteúdo do quadro de texto em colunas
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Imprima o texto de cada coluna no console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorno:**
java.lang.String[] - Um array de strings, onde cada string representa o conteúdo de texto de uma coluna específica no [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Se o TextFrame não contiver múltiplas colunas, o array retornado terá um único elemento contendo o texto completo. Colunas vazias serão representadas como strings vazias no array.
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```


Realça todas as correspondências do texto de exemplo com a cor especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | O texto a ser realçado. |
| highlightColor | java.lang.Integer | A cor para realçar o texto. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opções de realce. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Realça todas as correspondências do texto de exemplo com a cor especificada.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // realçando todas as palavras 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // realçando todas as ocorrências separadas de 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | O texto a ser realçado. |
| highlightColor | java.lang.Integer | A cor para realçar o texto. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opções de pesquisa de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber os resultados da pesquisa [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```


Realça todas as correspondências da expressão regular com a cor especificada.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // realçando todas as palavras com 5 símbolos ou mais
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A expressão regular java.util.regex.Pattern para obter strings a serem realçadas. |
| highlightColor | java.lang.Integer | A cor para realçar o texto. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber os resultados da pesquisa [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```


Realça todas as correspondências da expressão regular com a cor especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | java.lang.String | Texto da expressão regular para obter o texto a ser realçado. |
| highlightColor | java.lang.Integer | A cor para realçar o texto. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opções de realce. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Substitui todas as ocorrências do texto especificado por outro texto especificado.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Substitua todas as ocorrências separadas de 'the' por '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oldText | java.lang.String | A string a ser substituída. |
| newText | java.lang.String | A string que substituirá todas as ocorrências de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opções de pesquisa de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber os resultados da pesquisa [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Substitui todas as correspondências da expressão regular pela string especificada.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Substitua todas as palavras com 5 símbolos ou mais por '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A expressão regular java.util.regex.Pattern para obter strings a serem substituídas. |
| newText | java.lang.String | A string que substituirá todas as ocorrências das strings a serem substituídas. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber os resultados da pesquisa [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |