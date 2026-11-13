---
title: TextFrame
second_title: Aspose.Slides for Java API Referansı
description: Bir TextFrame'i temsil eder.
type: docs
url: /tr/com.aspose.slides/textframe/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Represents a TextFrame.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Bir çerçevedeki tüm paragraf listesini döndürür. |
| [getText()](#getText--) | Bir TextFrame için düz metni alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir TextFrame için düz metni alır veya ayarlar. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Bu TextFrame nesnesi için biçimlendirme nesnesini döndürür. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | İçerilen köprüleri kolayca erişim sağlar. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe)'nin metin içeriğini bir dizi stringe böler, her öğe çerçevedeki ayrı bir metin sütununa karşılık gelir. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Belirtilen metnin tüm görünümlerini başka bir belirtilen metinle değiştirir. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Düzenli ifadeye ait tüm eşleşmeleri belirtilen dizgeyle değiştirir. |
| [getSlide()](#getSlide--) | Bir TextFrame'in üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Bir TextFrame'in üst sunumunu döndürür. |
| [getParentShape()](#getParentShape--) | Üst şekli döndürür veya üst nesne IShape arayüzünü uygulamıyorsa null döndürür. Yalnızca okunabilir [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | Üst şeklin geometrisi tarafından tanımlanan metin dikdörtgenini alır. |
| [getParentCell()](#getParentCell--) | Üst hücreyi döndürür veya üst nesne ICell arayüzünü uygulamıyorsa null döndürür. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Yalnızca okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```


Bir çerçevedeki tüm paragraf listesini döndürür. Yalnızca okunabilir [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Döndürür:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```


Bir TextFrame için düz metni alır veya ayarlar. Okunabilir ve yazılabilir String.

Değer: Metin.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Bir TextFrame için düz metni alır veya ayarlar. Okunabilir ve yazılabilir String.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```


Bu TextFrame nesnesi için biçimlendirme nesnesini döndürür. Yalnızca okunabilir [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Döndürür:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


İçerilen köprüleri kolayca erişim sağlar. Yalnızca okunabilir [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Döndürür:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir.
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Vurgulanacak örnek metin. |
| highlightColor | java.awt.Color | Metni vurgulamak için renk. |
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```


Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // highlighting all words 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // highlighting all separate 'the' occurrences
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Vurgulanacak metin. |
| highlightColor | java.awt.Color | Metni vurgulamak için renk. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Vurgulama seçenekleri. |
### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```


[ITextFrame](../../com.aspose.slides/itextframe)'nin metin içeriğini bir dizi stringe böler, her öğe çerçeve içindeki ayrı bir metin sütununa karşılık gelir.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // İlk şekli slaytta al ve ITextFrame tipine dönüştür
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Metin çerçevesi içeriğini sütunlara böl
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Her sütunun metnini konsola yazdır
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
java.lang.String[] - Bir dizi string, her string [ITextFrame](../../com.aspose.slides/itextframe)'deki belirli bir sütunun metin içeriğini temsil eder.

--------------------

Metin çerçevesi birden çok sütun içermiyorsa, döndürülen dizi tam metni içeren tek bir öğe içerir. Boş sütunlar dizede boş string olarak temsil edilir.
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // highlighting all words 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // highlighting all separate 'the' occurrences
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Vurgulanacak metin. |
| highlightColor | java.awt.Color | Metni vurgulamak için renk. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Metin arama seçenekleri [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```


Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // 10 sembolden uzun tüm sözcükleri vurgulama
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | java.lang.String | Vurgulanacak düzenli ifadenin metni. |
| highlightColor | java.awt.Color | Metni vurgulamak için renk. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Vurgulama seçenekleri. |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5 sembolden uzun tüm sözcükleri vurgulama
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Vurgulanacak dizgeleri elde etmek için java.util.regex.Pattern düzenli ifadesi. |
| highlightColor | java.awt.Color | Metni vurgulamak için renk. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Belirtilen metnin tüm görünümlerini başka bir belirtilen metinle değiştirir.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Tüm ayrı 'the' oluşumlarını '***' ile değiştir
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldText | java.lang.String | Değiştirilecek dize. |
| newText | java.lang.String | oldText'in tüm görünümlerini değiştirecek dize. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Metin arama seçenekleri [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Değiştirme işlemi sonucunu kaydetmek için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Düzenli ifadeye ait tüm eşleşmeleri belirtilen dizgeyle değiştirir.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5 sembolden uzun tüm sözcükleri '***' ile değiştir
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Değiştirilecek dizgeleri elde etmek için java.util.regex.Pattern düzenli ifadesi. |
| newText | java.lang.String | Değiştirilecek tüm dizgeleri içeren dize. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Değiştirme işlemi sonucunu kaydetmek için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Bir TextFrame'in üst slaytını döndürür. Yalnızca okunabilir [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Bir TextFrame'in üst sunumunu döndürür. Yalnızca okunabilir [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```


Üst şekli döndürür veya üst nesne IShape arayüzünü uygulamıyorsa null döndürür. Yalnızca okunabilir [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Bu doğrulamalar her zaman doğrudur
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
[IShape](../../com.aspose.slides/ishape)
### getTextRect() {#getTextRect--}
```
public final Rectangle2D.Float getTextRect()
```


Üst şeklin geometrisi tarafından tanımlanan metin dikdörtgenini alır.

**Döndürür:**
java.awt.geom.Rectangle2D.Float - Metin alanını tanımlayan bir java.awt.geom.Rectangle2D.Float.

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```


Üst hücreyi döndürür veya üst nesne ICell arayüzünü uygulamıyorsa null döndürür. Yalnızca okunabilir [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Bu doğrulamalar her zaman doğrudur
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
[ICell](../../com.aspose.slides/icell)