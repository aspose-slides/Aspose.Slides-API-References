---
title: ITextFrame
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir TextFrame'i temsil eder.
type: docs
url: /tr/com.aspose.slides/itextframe/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Bir TextFrame'i temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Bir çerçevedeki tüm paragrafların listesini döndürür. |
| [getText()](#getText--) | Bir TextFrame için düz metni alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir TextFrame için düz metni alır veya ayarlar. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Bu TextFrame nesnesi için biçimlendirme nesnesini döndürür. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | İçerilen köprülere kolay erişim sağlar. |
| [getParentShape()](#getParentShape--) | Üst şekli döndürür veya üst nesne IShape arayüzünü uygulamıyorsa null döndürür. Yalnızca okunabilir [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Üst hücreyi döndürür veya üst nesne ICell arayüzünü uygulamıyorsa null döndürür. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Tüm paragraflarda aynı biçimlendirmeye sahip bölümleri birleştirir. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe) metin içeriğini, her bir öğenin çerçeve içinde ayrı bir metin sütununa karşılık geldiği bir dizi dizeye böler. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Belirtilen metnin tüm görünümlerini başka bir belirtilen metinle değiştirir. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Bir çerçevedeki tüm paragrafların listesini döndürür. Yalnızca okunabilir [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Döndürür:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

Bir TextFrame için düz metni alır veya ayarlar. Okunabilir/Yazılabilir String.

Değer: Metin.

**Döndürür:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Bir TextFrame için düz metni alır veya ayarlar. Okunabilir/Yazılabilir String.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Bu TextFrame nesnesi için biçimlendirme nesnesini döndürür. Yalnızca okunabilir [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Döndürür:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

İçerilen köprülere kolay erişim sağlar. Yalnızca okunabilir [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Döndürür:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
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

### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
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

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Tüm paragraflarda aynı biçimlendirmeye sahip bölümleri birleştirir.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Vurgulanacak metin. |
| highlightColor | java.lang.Integer | Metni vurgulamak için renk. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

[ITextFrame](../../com.aspose.slides/itextframe) metin içeriğini, her bir öğenin çerçeve içinde ayrı bir metin sütununa karşılık geldiği bir dizi dizeye böler.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // İlk şekli slaytta al ve ITextFrame'e dönüştür
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
java.lang.String[] - Her bir dize, [ITextFrame](../../com.aspose.slides/itextframe) içindeki belirli bir sütunun metin içeriğini temsil eden bir dizi dize.

If the text frame does not contain multiple columns, the returned array will have a single element containing the full text. Empty columns will be represented as empty strings in the array.

Metin çerçevesi birden fazla sütun içermiyorsa, döndürülen dizi tam metni içeren tek bir öğeye sahip olacaktır. Boş sütunlar dizi içinde boş dizeler olarak temsil edilir.

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Vurgulanacak metin. |
| highlightColor | java.lang.Integer | Metni vurgulamak için renk. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Vurgulama seçenekleri. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
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
>      // tüm 'important' kelimelerini vurgulama
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // tüm ayrı 'the' oluşumlarını vurgulama
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
| highlightColor | java.lang.Integer | Metni vurgulamak için renk. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Metin arama seçenekleri [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5 karakter veya daha uzun tüm kelimeleri vurgulama
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Vurgulamak için dizeleri elde etmek amacıyla java.util.regex.Pattern düzenli ifadesi. |
| highlightColor | java.lang.Integer | Metni vurgulamak için renk. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | java.lang.String | Vurgulamak için metni elde etmek amacıyla düzenli ifadenin metni. |
| highlightColor | java.lang.Integer | Metni vurgulamak için renk. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Vurgulama seçenekleri. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Belirtilen metnin tüm görünümlerini başka bir belirtilen metinle değiştirir.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5 sembol veya daha uzun tüm kelimeleri '***' ile değiştir
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Değiştirilecek dizeleri elde etmek amacıyla java.util.regex.Pattern düzenli ifadesi. |
| newText | java.lang.String | Değiştirilecek dizelerin tüm görünümlerini değiştirecek dize. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |