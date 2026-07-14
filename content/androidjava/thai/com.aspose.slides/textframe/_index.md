---
title: TextFrame
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: เป็นตัวแทนของ TextFrame.
type: docs
url: /th/com.aspose.slides/textframe/
---
**สืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

เป็นตัวแทนของ TextFrame.
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | คืนรายการของย่อหน้าทั้งหมดในเฟรม |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame |
| [getTextFrameFormat()](#getTextFrameFormat--) | คืนอ็อบเจ็กต์การจัดรูปแบบสำหรับ TextFrame นี้ |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงไฮเปอร์ลิงก์ที่ประกอบอยู่ได้อย่างง่ายดาย |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [splitTextByColumns()](#splitTextByColumns--) | แบ่งเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาร์เรย์ของสตริง, โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกในเฟรม |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับนิพจน์ปรกติด้วยสีที่ระบุ |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับนิพจน์ปรกติด้วยสีที่ระบุ |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกตำแหน่งที่ตรงกับนิพจน์ปรกติด้วยสตริงที่ระบุ |
| [getSlide()](#getSlide--) | คืนสไลด์พาเรนต์ของ TextFrame |
| [getPresentation()](#getPresentation--) | คืนพรีเซนเทชันพาเรนต์ของ TextFrame |
| [getParentShape()](#getParentShape--) | คืนรูปร่างพาเรนต์หรือ null หากอ็อบเจ็กต์พาเรนต์ไม่ทำการใช้งานอินเทอร์เฟซ IShape Read-only [IShape](../../com.aspose.slides/ishape) |
| [getParentCell()](#getParentCell--) | คืนเซลล์พาเรนต์หรือ null หากอ็อบเจ็กต์พาเรนต์ไม่ทำการใช้งานอินเทอร์เฟซ ICell |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนอ็อบเจ็กต์ Parent_Immediate. Read-only IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

คืนรายการของย่อหน้าทั้งหมดในเฟรม. Read-only [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**คืนค่า:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```

รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame. Read/write String.

Value: The text.

**คืนค่า:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame. Read/write String.

Value: The text.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

คืนอ็อบเจ็กต์การจัดรูปแบบสำหรับ TextFrame นี้. Read-only [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**คืนค่า:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงไฮเปอร์ลิงก์ที่ประกอบอยู่ได้อย่างง่ายดาย. Read-only [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**คืนค่า:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

รวมรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ตัวอย่างข้อความที่ต้องการไฮไลท์ |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // ไฮไลท์คำทั้งหมด 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // ไฮไลท์การปรากฏแยกของ 'the'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการไฮไลท์ |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการไฮไลท์ |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

แบ่งเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาร์เรย์ของสตริง, โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกในเฟรม.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // รับรูปแรกบนสไลด์และแคสท์เป็น ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // แยกเนื้อหาข้อความของ TextFrame เป็นคอลัมน์
>      String[] columnsText = textFrame.splitTextByColumns();
>      // พิมพ์ข้อความของแต่ละคอลัมน์ไปยังคอนโซล
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
java.lang.String[] - อาร์เรย์ของสตริง, โดยแต่ละสตริงแทนเนื้อหาข้อความของคอลัมน์เฉพาะใน [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

หาก TextFrame ไม่มีหลายคอลัมน์, อาร์เรย์ที่คืนจะมีหนึ่งองค์ประกอบที่บรรจุข้อความทั้งหมด. คอลัมน์ที่ว่างจะถูกแทนด้วยสตริงว่างในอาร์เรย์.
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // ไฮไลท์คำทั้งหมด 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // ไฮไลท์การปรากฏแยกของ 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการไฮไลท์ |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

ไฮไลท์ทุกตำแหน่งที่ตรงกับนิพจน์ปรกติด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // ไฮไลท์คำทั้งหมดที่มีความยาว 10 สัญลักษณ์หรือมากกว่า
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.lang.String | ข้อความของนิพจน์ปรกติเพื่อให้ได้ข้อความที่ต้องการไฮไลท์ |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการไฮไลท์ |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

ไฮไลท์ทุกตำแหน่งที่ตรงกับนิพจน์ปรกติด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // ไฮไลท์คำทั้งหมดที่มีความยาว 5 สัญลักษณ์หรือมากกว่า
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ปรกติ java.util.regex.Pattern เพื่อให้ได้สตริงที่ต้องการไฮไลท์ |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การปรากฏแยกของ 'the' ด้วย '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | สตริงที่ต้องการแทนที่ |
| newText | java.lang.String | สตริงที่ใช้แทนที่ทุกการปรากฏของ oldText |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับบันทึกผลลัพธ์การแทนที่ [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

แทนที่ทุกตำแหน่งที่ตรงกับนิพจน์ปรกติด้วยสตริงที่ระบุ.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // แทนที่คำทั้งหมดที่มีความยาว 5 สัญลักษณ์หรือมากกว่า ด้วย '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ปรกติ java.util.regex.Pattern เพื่อให้ได้สตริงที่ต้องการแทนที่ |
| newText | java.lang.String | สตริงที่ใช้แทนที่ทุกการปรากฏของสตริงที่ต้องการแทนที่ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับบันทึกผลลัพธ์การแทนที่ [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนสไลด์พาเรนต์ของ TextFrame. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนพรีเซนเทชันพาเรนต์ของ TextFrame. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

คืนรูปร่างพาเรนต์หรือ null หากอ็อบเจ็กต์พาเรนต์ไม่ทำการใช้งานอินเทอร์เฟซ IShape Read-only [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // การตรวจสอบเหล่านี้เป็นจริงเสมอ
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

คืนเซลล์พาเรนต์หรือ null หากอ็อบเจ็กต์พาเรนต์ไม่ทำการใช้งานอินเทอร์เฟซ ICell. Read-only [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // การตรวจสอบเหล่านี้เป็นจริงเสมอ
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**
[ICell](../../com.aspose.slides/icell)