---
title: TextFrame
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een TextFrame voor.
type: docs
url: /nl/com.aspose.slides/textframe/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Stelt een TextFrame voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Retourneert de lijst van alle alinea's in een frame. |
| [getText()](#getText--) | Haalt of stelt de platte tekst voor een TextFrame in. |
| [setText(String value)](#setText-java.lang.String-) | Haalt of stelt de platte tekst voor een TextFrame in. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Retourneert het opmaakobject voor dit TextFrame-object. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot ingesloten hyperlinks. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs met dezelfde opmaak samen in alle alinea's. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [splitTextByColumns()](#splitTextByColumns--) | Splitst de tekstinhoud van de [ITextFrame](../../com.aspose.slides/itextframe) in een array van strings, waarbij elk element overeenkomt met een afzonderlijke tekstkolom binnen het frame. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een TextFrame. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een TextFrame. |
| [getParentShape()](#getParentShape--) | Retourneert de bovenliggende vorm of null als het bovenliggende object de IShape-interface niet implementeert Alleen-lezen [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Retourneert de bovenliggende cel of null als het bovenliggende object de ICell-interface niet implementeert. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Retourneert de lijst van alle alinea's in een frame. Alleen-lezen [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Retourneert:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```

Haalt of stelt de platte tekst voor een TextFrame in. Lezen/schrijven String.

Waarde: De tekst.

**Retourneert:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Haalt of stelt de platte tekst voor een TextFrame in. Lezen/schrijven String.

Waarde: De tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

Retourneert het opmaakobject voor dit TextFrame-object. Alleen-lezen [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Retourneert:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Biedt gemakkelijke toegang tot ingesloten hyperlinks. Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retourneert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Voegt runs met dezelfde opmaak samen in alle alinea's.
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Voorbeeldtekst om te markeren. |
| highlightColor | java.lang.Integer | De kleur om de tekst te markeren. |
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // markeren van alle woorden 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // markeren van alle afzonderlijke 'the'-voorkomens
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | De tekst om te markeren. |
| highlightColor | java.lang.Integer | De kleur om de tekst te markeren. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Markeeropties. |
### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Splitst de tekstinhoud van de [ITextFrame](../../com.aspose.slides/itextframe) in een array van strings, waarbij elk element overeenkomt met een afzonderlijke tekstkolom binnen het frame.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Haal de eerste vorm op de dia op en cast deze naar ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Splits de inhoud van het tekstframe in kolommen
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Print de tekst van elke kolom naar de console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
java.lang.String[] - Een array van strings, waarbij elke string de tekstinhoud van een specifieke kolom in de [ITextFrame](../../com.aspose.slides/itextframe) vertegenwoordigt.

--------------------

Als het tekstframe geen meerdere kolommen bevat, zal de geretourneerde array één element bevatten met de volledige tekst. Lege kolommen worden weergegeven als lege strings in de array.
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> De volgende codevoorbeeld laat zien hoe tekst gemarkeerd kan worden in een TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // markeren van alle woorden 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // markeren van alle afzonderlijke 'the'-voorkomens
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | De tekst om te markeren. |
| highlightColor | java.lang.Integer | De kleur om de tekst te markeren. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // markeren van alle woorden met 10 tekens of langer
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | java.lang.String | Tekst van reguliere expressie om te markeren. |
| highlightColor | java.lang.Integer | De kleur om de tekst te markeren. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Markeeropties. |
### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // markeren van alle woorden met 5 tekens of langer
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om te markeren. |
| highlightColor | java.lang.Integer | De kleur om de tekst te markeren. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Vervang alle afzonderlijke 'the'-voorkomens door '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldText | java.lang.String | De te vervangen string. |
| newText | java.lang.String | De string om alle voorkomens van oldText te vervangen. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-object voor het opslaan van het resultaat van de vervangingsoperatie [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Vervang alle woorden met 5 tekens of langer door '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om te vervangen strings te verkrijgen. |
| newText | java.lang.String | De string om alle voorkomens van de te vervangen strings te vervangen. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-object voor het opslaan van het resultaat van de vervangingsoperatie [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een TextFrame. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een TextFrame. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Retourneert de bovenliggende vorm of null als het bovenliggende object de IShape-interface niet implementeert Alleen-lezen [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Deze beweringen zijn altijd waar
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

Retourneert de bovenliggende cel of null als het bovenliggende object de ICell-interface niet implementeert Alleen-lezen [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Deze beweringen zijn altijd waar
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retourneert:**
[ICell](../../com.aspose.slides/icell)