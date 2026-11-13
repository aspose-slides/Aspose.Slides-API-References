---
title: ITextFrame
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een TextFrame voor.
type: docs
url: /nl/com.aspose.slides/itextframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Stelt een TextFrame voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Retourneert de lijst met alle alinea's in een frame. |
| [getText()](#getText--) | Haalt of stelt de platte tekst in voor een TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Haalt of stelt de platte tekst in voor een TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Retourneert het opmaakobject voor dit TextFrame-object. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot ingesloten hyperlinks. |
| [getParentShape()](#getParentShape--) | Retourneert de bovenliggende vorm of null als het bovenliggende object de IShape-interface niet implementeert Alleen-lezen [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | Haalt het tekstrectangel op dat is gedefinieerd door de geometrie van de bovenliggende vorm. |
| [getParentCell()](#getParentCell--) | Retourneert de bovenliggende cel of null als het bovenliggende object de ICell-interface niet implementeert. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs samen met dezelfde opmaak in alle alinea's. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [splitTextByColumns()](#splitTextByColumns--) | Splitst de tekstinhoud van de [ITextFrame](../../com.aspose.slides/itextframe) in een array van strings, waarbij elk element overeenkomt met een afzonderlijke tekstkolom binnen het frame. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```


Retourneert de lijst met alle alinea's in een frame. Alleen-lezen [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Retour:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```


Haalt of stelt de platte tekst in voor een TextFrame. Lezen/Schrijven String.

Waarde: De tekst.

**Retour:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Haalt of stelt de platte tekst in voor een TextFrame. Lezen/Schrijven String.

Waarde: De tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```


Retourneert het opmaakobject voor dit TextFrame-object. Alleen-lezen [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Retour:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Biedt gemakkelijke toegang tot ingesloten hyperlinks. Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retour:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
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


**Retour:**
[IShape](../../com.aspose.slides/ishape)
### getTextRect() {#getTextRect--}
```
public abstract Rectangle2D.Float getTextRect()
```


Haalt het tekstrectangel op dat is gedefinieerd door de geometrie van de bovenliggende vorm.

**Retour:**
java.awt.geom.Rectangle2D.Float - Een java.awt.geom.Rectangle2D.Float die het tekstgebied definieert.

--------------------

De rechthoekcoördinaten zijn relatief ten opzichte van de linkerbovenhoek van de bovenliggende vorm.
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
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


**Retour:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Voegt runs samen met dezelfde opmaak in alle alinea's.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```


Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | De te markeren tekst. |
| highlightColor | java.awt.Color | De kleur waarmee de tekst gemarkeerd wordt. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```


Splitst de tekstinhoud van de [ITextFrame](../../com.aspose.slides/itextframe) in een array van strings, waarbij elk element overeenkomt met een afzonderlijke tekstkolom binnen het frame.

--------------------

> ```
> Het volgende voorbeeld toont hoe #splitTextByColumns.splitTextByColumns te gebruiken is:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Haal de eerste vorm op de dia en cast deze naar ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Split de inhoud van het tekstframe in kolommen
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Print de tekst van elke kolom naar de console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
java.lang.String[] - Een array van strings, waarbij elke string de tekstinhoud van een specifieke kolom in de [ITextFrame](../../com.aspose.slides/itextframe) vertegenwoordigt.

--------------------

Als het tekstframe geen meerdere kolommen bevat, zal de teruggegeven array één element bevatten met de volledige tekst. Lege kolommen worden in de array weergegeven als lege strings.
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```


Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | De te markeren tekst. |
| highlightColor | java.awt.Color | De kleur waarmee de tekst gemarkeerd wordt. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Markeeropties. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // markeren van alle woorden 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // markeren van alle afzonderlijke 'the' voorkomens
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | De te markeren tekst. |
| highlightColor | java.awt.Color | De kleur waarmee de tekst gemarkeerd wordt. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
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
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om strings te verkrijgen die gemarkeerd moeten worden. |
| highlightColor | java.awt.Color | De kleur waarmee de tekst gemarkeerd wordt. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```


Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | java.lang.String | Tekst van de reguliere expressie om te markeren. |
| highlightColor | java.awt.Color | De kleur waarmee de tekst gemarkeerd wordt. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Markeeropties. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Vervang alle afzonderlijke 'the' voorkomens door '***'
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
| newText | java.lang.String | De string die alle voorkomens van oldText vervangt. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
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
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om strings te verkrijgen die vervangen moeten worden. |
| newText | java.lang.String | De string die alle voorkomens van de te vervangen strings vervangt. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |