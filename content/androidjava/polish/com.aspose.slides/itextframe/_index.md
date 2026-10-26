---
title: ITextFrame
second_title: Aspose.Slides dla Androida – Referencja API Java
description: Reprezentuje TextFrame.
type: docs
url: /pl/com.aspose.slides/itextframe/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Reprezentuje TextFrame.
## Metody

| Metoda | Opis |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Zwraca listę wszystkich akapitów w ramce. |
| [getText()](#getText--) | Pobiera lub ustawia zwykły tekst dla TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Pobiera lub ustawia zwykły tekst dla TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Zwraca obiekt formatowania dla tego obiektu TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Umożliwia łatwy dostęp do zawartych hiperłączy. |
| [getParentShape()](#getParentShape--) | Zwraca nadrzędny kształt lub null, jeśli obiekt nadrzędny nie implementuje interfejsu IShape. Tylko do odczytu [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Zwraca nadrzędną komórkę lub null, jeśli obiekt nadrzędny nie implementuje interfejsu ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Podświetla wszystkie dopasowania tekstu przykładowego określonym kolorem. |
| [splitTextByColumns()](#splitTextByColumns--) | Dzieli zawartość tekstową [ITextFrame](../../com.aspose.slides/itextframe) na tablicę ciągów znaków, gdzie każdy element odpowiada oddzielnej kolumnie tekstowej w ramce. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Podświetla wszystkie dopasowania tekstu przykładowego określonym kolorem. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Podświetla wszystkie dopasowania tekstu przykładowego określonym kolorem. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zastępuje wszystkie wystąpienia określonego tekstu innym podanym tekstem. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Zwraca listę wszystkich akapitów w ramce. Tylko do odczytu [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Zwraca:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```

Pobiera lub ustawia zwykły tekst dla TextFrame. Odczyt/Zapis String.

Wartość: Tekst.

**Zwraca:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Pobiera lub ustawia zwykły tekst dla TextFrame. Odczyt/Zapis String.

Wartość: Tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Zwraca obiekt formatowania dla tego obiektu TextFrame. Tylko do odczytu [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Zwraca:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Umożliwia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Zwraca:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

Zwraca nadrzędny kształt lub null, jeśli obiekt nadrzędny nie implementuje interfejsu IShape. Tylko do odczytu [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Te asercje są zawsze prawdziwe
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

Zwraca nadrzędną komórkę lub null, jeśli obiekt nadrzędny nie implementuje interfejsu ICell. Tylko do odczytu [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Te asercje są zawsze prawdziwe
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Podświetla wszystkie dopasowania tekstu przykładowego określonym kolorem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do podświetlenia. |
| highlightColor | java.lang.Integer | Kolor używany do podświetlenia tekstu. |
### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Dzieli zawartość tekstową [ITextFrame](../../com.aspose.slides/itextframe) na tablicę ciągów znaków, gdzie każdy element odpowiada osobnej kolumnie tekstowej w ramce.

--------------------

> ```
> Poniższy przykład demonstruje, jak użyć #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Pobierz pierwszy kształt na slajdzie i rzutuj go na ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Podziel zawartość ramki tekstowej na kolumny
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Wypisz tekst każdej kolumny na konsolę
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
java.lang.String[] - Tablica ciągów znaków, gdzie każdy ciąg reprezentuje zawartość tekstową konkretnej kolumny w [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Jeśli ramka tekstowa nie zawiera wielu kolumn, zwrócona tablica będzie miała pojedynczy element zawierający cały tekst. Puste kolumny będą reprezentowane jako puste ciągi znaków w tablicy.
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Podświetla wszystkie dopasowania tekstu przykładowego określonym kolorem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do podświetlenia. |
| highlightColor | java.lang.Integer | Kolor używany do podświetlenia tekstu. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opcje podświetlania. |
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Podświetla wszystkie dopasowania tekstu przykładowego określonym kolorem.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // podświetlanie wszystkich słów 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // podświetlanie wszystkich oddzielnych wystąpień 'the' occurrences
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do podświetlenia. |
| highlightColor | java.lang.Integer | Kolor używany do podświetlenia tekstu. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // podświetlanie wszystkich słów o długości 5 znaków lub więcej
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern, którego ciągi mają być podświetlone. |
| highlightColor | java.lang.Integer | Kolor używany do podświetlenia tekstu. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | java.lang.String | Tekst wyrażenia regularnego, którego tekst ma być podświetlony. |
| highlightColor | java.lang.Integer | Kolor używany do podświetlenia tekstu. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opcje podświetlania. |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Zastępuje wszystkie wystąpienia określonego tekstu innym podanym tekstem.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Zastąp wszystkie oddzielne wystąpienia 'the' ciągiem '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| oldText | java.lang.String | Ciąg znaków do zastąpienia. |
| newText | java.lang.String | Ciąg znaków, który zastąpi wszystkie wystąpienia oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem.

--------------------

> ```
> Poniższy przykład kodu pokazuje, jak zamienić tekst przy użyciu wyrażenia regularnego na określony ciąg.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Zamień wszystkie słowa o długości 5 znaków lub więcej na '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern, którego ciągi mają być zastąpione. |
| newText | java.lang.String | Ciąg znaków, który zastąpi wszystkie wystąpienia ciągów do zastąpienia. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |