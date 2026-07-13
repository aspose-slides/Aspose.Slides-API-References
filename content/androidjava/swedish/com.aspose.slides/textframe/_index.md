---
title: TextFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en TextFrame.
type: docs
url: /sv/com.aspose.slides/textframe/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Representerar en TextFrame.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Returnerar listan med alla stycken i en ram. |
| [getText()](#getText--) | Hämtar eller sätter den enkla texten för ett TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller sätter den enkla texten för ett TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Returnerar formateringsobjektet för detta TextFrame-objekt. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Slår ihop körningar med samma formatering i alla stycken. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [splitTextByColumns()](#splitTextByColumns--) | Delar upp textinnehållet i [ITextFrame](../../com.aspose.slides/itextframe) i en array av strängar, där varje element motsvarar en separat textkolumn inom ramen. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Markerar alla träffar av reguljärt uttryck med den angivna färgen. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Markerar alla träffar av reguljärt uttryck med den angivna färgen. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersätter alla träffar av reguljärt uttryck med angiven sträng. |
| [getSlide()](#getSlide--) | Returnerar föräldrasliden för ett TextFrame. |
| [getPresentation()](#getPresentation--) | Returnerar föräldrapresentationen för ett TextFrame. |
| [getParentShape()](#getParentShape--) | Returnerar föräldrakonturen eller null om föräldraobjektet inte implementerar IShape-gränssnittet. Läs-endast [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Returnerar föräldrcellen eller null om föräldraobjektet inte implementerar ICell-gränssnittet. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Läs-endast IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Returnerar listan med alla stycken i en ram. Läs-endast [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Returnerar:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

Hämtar eller sätter den enkla texten för ett TextFrame. Läs/skriv String.

Värde: Texten.

**Returnerar:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Hämtar eller sätter den enkla texten för ett TextFrame. Läs/skriv String.

Värde: Texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

Returnerar formateringsobjektet för detta TextFrame-objekt. Läs-endast [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Returnerar:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Tillhandahåller enkel åtkomst till inbäddade hyperlänkar. Läs-endast [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returnerar:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Slår ihop körningar med samma formatering i alla stycken.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Markerar alla träffar av exempeltexten med den angivna färgen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Exempeltext att markera. |
| highlightColor | java.lang.Integer | Färgen för att markera texten. |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Markerar alla träffar av exempeltexten med den angivna färgen.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // markerar alla ord 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // markerar alla separata 'the' förekomster
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten att markera. |
| highlightColor | java.lang.Integer | Färgen för att markera texten. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Markeringsalternativ. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Delar upp textinnehållet i [ITextFrame](../../com.aspose.slides/itextframe) i en array av strängar, där varje element motsvarar en separat textkolumn inom ramen.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Hämta den första formen på bilden och kasta den till ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Dela upp textramens innehåll i kolumner
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Skriv ut varje kolumns text till konsolen
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
java.lang.String[] - En array av strängar, där varje sträng representerar textinnehållet i en specifik kolumn i [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Om textramen inte innehåller flera kolumner kommer den returnerade arrayen att ha ett enda element som innehåller hela texten. Tomma kolumner kommer att representeras som tomma strängar i arrayen.

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Markerar alla träffar av exempeltexten med den angivna färgen.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // markerar alla ord 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // markerar alla separata 'the' förekomster
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten att markera. |
| highlightColor | java.lang.Integer | Färgen för att markera texten. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text sökalternativ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Markerar alla träffar av reguljärt uttryck med den angivna färgen.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // markerar alla ord med 10 tecken eller längre
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | java.lang.String | Text för reguljärt uttryck för att hämta text att markera. |
| highlightColor | java.lang.Integer | Färgen för att markera texten. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Markeringsalternativ. |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Markerar alla träffar av reguljärt uttryck med den angivna färgen.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // markerar alla ord med 5 tecken eller längre
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Det reguljära uttrycket java.util.regex.Pattern för att hämta strängar att markera. |
| highlightColor | java.lang.Integer | Färgen för att markera texten. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Ersätter alla förekomster av den angivna texten med en annan angiven text.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ersätt alla separata 'the'-förekomster med '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldText | java.lang.String | Strängen som skall ersättas. |
| newText | java.lang.String | Strängen som ersätter alla förekomster av oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text sökalternativ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objekt för att spara resultatet av ersättningsoperationen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Ersätter alla träffar av reguljärt uttryck med angiven sträng.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Ersätt alla ord med 5 tecken eller längre med '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Det reguljära uttrycket java.util.regex.Pattern för att hämta strängar som skall ersättas. |
| newText | java.lang.String | Strängen som ersätter alla förekomster av strängar som skall ersättas. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objekt för att spara resultatet av ersättningsoperationen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar föräldrasliden för ett TextFrame. Läs-endast [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar föräldrapresentationen för ett TextFrame. Läs-endast [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Returnerar föräldrakonturen eller null om föräldraobjektet inte implementerar IShape-gränssnittet. Läs-endast [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Dessa påståenden är alltid sanna
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

Returnerar föräldrcellen eller null om föräldraobjektet inte implementerar ICell-gränssnittet. Läs-endast [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Dessa påståenden är alltid sanna
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
[ICell](../../com.aspose.slides/icell)