---
title: TextFrame
second_title: Odwołanie API Aspose.Slides dla Javy
description: Reprezentuje TextFrame.
type: docs
url: /pl/com.aspose.slides/textframe/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Reprezentuje TextFrame.
## Metody

| Metoda | Opis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Zwraca listę wszystkich akapitów w ramce. |
| [getText()](#getText--) | Pobiera lub ustawia zwykły tekst dla TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Pobiera lub ustawia zwykły tekst dla TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Zwraca obiekt formatowania dla tego obiektu TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Zapewnia łatwy dostęp do zawartych hiperłączy. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Podświetla wszystkie wystąpienia tekstu przykładowego określonym kolorem. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Podświetla wszystkie wystąpienia tekstu przykładowego określonym kolorem. |
| [splitTextByColumns()](#splitTextByColumns--) | Dzieli zawartość tekstową [ITextFrame](../../com.aspose.slides/itextframe) na tablicę łańcuchów, przy czym każdy element odpowiada oddzielnej kolumnie tekstowej w ramce. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Podświetla wszystkie wystąpienia tekstu przykładowego określonym kolorem. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Podświetla wszystkie wystąpienia wyrażenia regularnego określonym kolorem. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Podświetla wszystkie wystąpienia wyrażenia regularnego określonym kolorem. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny TextFrame. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną TextFrame. |
| [getParentShape()](#getParentShape--) | Zwraca kształt nadrzędny lub null, jeśli obiekt nadrzędny nie implementuje interfejsu IShape. Tylko do odczytu [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | Pobiera prostokąt tekstowy zdefiniowany przez geometrię kształtu nadrzędnego. |
| [getParentCell()](#getParentCell--) | Zwraca komórkę nadrzędną lub null, jeśli obiekt nadrzędny nie implementuje interfejsu ICell. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```


Zwraca listę wszystkich akapitów w ramce. Tylko do odczytu [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Zwraca:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```


Pobiera lub ustawia zwykły tekst dla TextFrame. Odczyt/zapis String.

Wartość: Tekst.

**Zwraca:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Pobiera lub ustawia zwykły tekst dla TextFrame. Odczyt/zapis String.

Wartość: Tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```


Zwraca obiekt formatowania dla tego obiektu TextFrame. Tylko do odczytu [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Zwraca:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Zapewnia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Zwraca:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach.
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


Podświetla wszystkie wystąpienia tekstu przykładowego określonym kolorem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Przykładowy tekst do podświetlenia. |
| highlightColor | java.awt.Color | Kolor użyty do podświetlenia tekstu. |
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```


Podświetla wszystkie wystąpienia tekstu przykładowego określonym kolorem.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // podświetlanie wszystkich słów 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // podświetlanie wszystkich oddzielnych wystąpień 'the'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do podświetlenia. |
| highlightColor | java.awt.Color | Kolor użyty do podświetlenia tekstu. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opcje podświetlania. |
### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```


Dzieli zawartość tekstową [ITextFrame](../../com.aspose.slides/itextframe) na tablicę łańcuchów, przy czym każdy element odpowiada oddzielnej kolumnie tekstowej w ramce.

--------------------

> ```
> Poniższy przykład demonstruje, jak używać #splitTextByColumns.splitTextByColumns:
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
java.lang.String[] – Tablica łańcuchów, w której każdy element reprezentuje zawartość tekstową określonej kolumny w [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Jeśli ramka tekstowa nie zawiera wielu kolumn, zwrócona tablica będzie miała jeden element zawierający cały tekst. Puste kolumny będą reprezentowane jako puste łańcuchy w tablicy.
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Podświetla wszystkie wystąpienia tekstu przykładowego określonym kolorem.

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
>      // podświetlanie wszystkich oddzielnych wystąpień 'the'
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
| highlightColor | java.awt.Color | Kolor użyty do podświetlenia tekstu. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego służący do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```


Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // podświetlanie wszystkich słów o długości 10 znaków lub więcej
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | java.lang.String | Tekst wyrażenia regularnego, którego wystąpienia mają być podświetlone. |
| highlightColor | java.awt.Color | Kolor użyty do podświetlenia tekstu. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opcje podświetlania. |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
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
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern, którego wystąpienia mają być podświetlone. |
| highlightColor | java.awt.Color | Kolor użyty do podświetlenia tekstu. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego służący do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem.

--------------------

> ```
> Poniższy przykładowy kod pokazuje, jak zamienić jeden określony ciąg znaków na inny określony ciąg znaków.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // zamień wszystkie oddzielne wystąpienia 'the' na '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| oldText | java.lang.String | Łańcuch, który ma zostać zastąpiony. |
| newText | java.lang.String | Łańcuch, którym zastąpione zostaną wszystkie wystąpienia oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego służący do zapisu wyniku operacji zamiany [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // zamień wszystkie słowa o długości 5 znaków lub dłuższe na '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern, którego dopasowania mają zostać zastąpione. |
| newText | java.lang.String | Łańcuch, którym zastąpione zostaną wszystkie dopasowania. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego służący do zapisu wyniku operacji zamiany [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Zwraca slajd nadrzędny TextFrame. Tylko do odczytu [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Zwraca prezentację nadrzędną TextFrame. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```


Zwraca kształt nadrzędny lub null, jeśli obiekt nadrzędny nie implementuje interfejsu IShape. Tylko do odczytu [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Te asercje zawsze są prawdziwe
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)
### getTextRect() {#getTextRect--}
```
public final Rectangle2D.Float getTextRect()
```


Pobiera prostokąt tekstowy zdefiniowany przez geometrię kształtu nadrzędnego.

**Zwraca:**
java.awt.geom.Rectangle2D.Float – Obiekt java.awt.geom.Rectangle2D.Float definiujący obszar tekstu.
### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```


Zwraca komórkę nadrzędną lub null, jeśli obiekt nadrzędny nie implementuje interfejsu ICell. Tylko do odczytu [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Te asercje zawsze są prawdziwe
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Zwraca:**
[ICell](../../com.aspose.slides/icell)