---
title: ITextFrame
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un TextFrame.
type: docs
url: /it/com.aspose.slides/itextframe/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Rappresenta un TextFrame.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Restituisce l'elenco di tutti i paragrafi in un frame. |
| [getText()](#getText--) | Ottiene o imposta il testo semplice per un TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo semplice per un TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Restituisce l'oggetto di formattazione per questo oggetto TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornisce un accesso facile ai collegamenti ipertestuali contenuti. |
| [getParentShape()](#getParentShape--) | Restituisce la forma genitore o null se l'oggetto genitore non implementa l'interfaccia IShape. Solo lettura [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Restituisce la cella genitore o null se l'oggetto genitore non implementa l'interfaccia ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce le porzioni con la stessa formattazione in tutti i paragrafi. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [splitTextByColumns()](#splitTextByColumns--) | Divide il contenuto testuale del [ITextFrame](../../com.aspose.slides/itextframe) in un array di stringhe, dove ogni elemento corrisponde a una colonna di testo separata all'interno del frame. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata. |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Restituisce l'elenco di tutti i paragrafi in un frame. Solo lettura [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Restituisce:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```

Ottiene o imposta il testo semplice per un TextFrame. Lettura/scrittura String.

Valore: Il testo.

**Restituisce:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Ottiene o imposta il testo semplice per un TextFrame. Lettura/scrittura String.

Valore: Il testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Restituisce l'oggetto di formattazione per questo oggetto TextFrame. Solo lettura [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Restituisce:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Fornisce un accesso facile ai collegamenti ipertestuali contenuti. Solo lettura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Restituisce:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

Restituisce la forma genitore o null se l'oggetto genitore non implementa l'interfaccia IShape. Solo lettura [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Queste asserzioni sono sempre vere
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

Restituisce la cella genitore o null se l'oggetto genitore non implementa l'interfaccia ICell. Solo lettura [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Queste asserzioni sono sempre vere
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Unisce le porzioni con la stessa formattazione in tutti i paragrafi.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Evidenzia tutte le occorrenze del testo di esempio con il colore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Il testo da evidenziare. |
| highlightColor | java.lang.Integer | Il colore con cui evidenziare il testo. |
### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Divide il contenuto testuale del [ITextFrame](../../com.aspose.slides/itextframe) in un array di stringhe, dove ogni elemento corrisponde a una colonna di testo separata all'interno del frame.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Ottieni la prima forma sulla diapositiva e convertila in ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Dividi il contenuto del text frame in colonne
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Stampa il testo di ciascuna colonna sulla console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
java.lang.String[] - Un array di stringhe, dove ogni stringa rappresenta il contenuto testuale di una colonna specifica nel [ITextFrame](../../com.aspose.slides/itextframe).

Se il text frame non contiene più colonne, l'array restituito avrà un unico elemento contenente il testo completo. Le colonne vuote saranno rappresentate come stringhe vuote nell'array.
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Evidenzia tutte le occorrenze del testo di esempio con il colore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Il testo da evidenziare. |
| highlightColor | java.lang.Integer | Il colore con cui evidenziare il testo. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opzioni di evidenziazione. |
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Evidenzia tutte le occorrenze del testo di esempio con il colore specificato.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // evidenzia tutte le parole 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // evidenzia tutte le occorrenze separate di 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Il testo da evidenziare. |
| highlightColor | java.lang.Integer | Il colore con cui evidenziare il testo. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // evidenzia tutte le parole con 5 o più simboli
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'espressione regolare java.util.regex.Pattern per ottenere le stringhe da evidenziare. |
| highlightColor | java.lang.Integer | Il colore con cui evidenziare il testo. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | java.lang.String | Testo dell'espressione regolare per ottenere il testo da evidenziare. |
| highlightColor | java.lang.Integer | Il colore con cui evidenziare il testo. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opzioni di evidenziazione. |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Sostituisci tutte le occorrenze separate di 'the' con '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldText | java.lang.String | La stringa da sostituire. |
| newText | java.lang.String | La stringa con cui sostituire tutte le occorrenze di oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Sostituisci tutte le parole con 5 simboli o più con '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'espressione regolare java.util.regex.Pattern per ottenere le stringhe da sostituire. |
| newText | java.lang.String | La stringa per sostituire tutte le occorrenze delle stringhe da sostituire. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback).