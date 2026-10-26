---
title: ITextFrame
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของ TextFrame.
type: docs
url: /th/com.aspose.slides/itextframe/
---
**All Implemented Interfaces:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Represents a TextFrame.  
## Methods

| Method | Description |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | คืนค่ารายการของย่อหน้าทั้งหมดในกรอบ |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame |
| [getTextFrameFormat()](#getTextFrameFormat--) | คืนค่าออบเจกต์การจัดรูปแบบสำหรับ TextFrame นี้ |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงลิงก์ที่ฝังอยู่ได้อย่างง่าย |
| [getParentShape()](#getParentShape--) | คืนค่า shape พาเรนท์หรือ null หากออบเจกต์พาเรนท์ไม่ได้ทำตามอินเทอร์เฟซ IShape อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape) |
| [getParentCell()](#getParentCell--) | คืนค่า cell พาเรนท์หรือ null หากออบเจกต์พาเรนท์ไม่ได้ทำตามอินเทอร์เฟซ ICell |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวม run ที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [splitTextByColumns()](#splitTextByColumns--) | แบ่งเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาเรย์ของสตริง โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกต่างหากภายในกรอบ |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับนิพจน์ประจำด้วยสีที่ระบุ |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | ไฮไลท์ทุกตำแหน่งที่ตรงกับนิพจน์ประจำด้วยสีที่ระบุ |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกตำแหน่งที่ตรงกับนิพจน์ประจำด้วยสตริงที่ระบุ |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

คืนค่ารายการของย่อหน้าทั้งหมดในกรอบ อ่านอย่างเดียว [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**ผลลัพธ์:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```

รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame อ่าน/เขียน String.

Value: ข้อความ.

**ผลลัพธ์:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame อ่าน/เขียน String.

Value: ข้อความ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

คืนค่าออบเจกต์การจัดรูปแบบสำหรับ TextFrame นี้ อ่านอย่างเดียว [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**ผลลัพธ์:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงลิงก์ที่ฝังอยู่ได้อย่างง่าย อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**ผลลัพธ์:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

คืนค่า shape พาเรนท์หรือ null หากออบเจกต์พาเรนท์ไม่ได้ทำตามอินเทอร์เฟซ IShape อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // การยืนยันเหล่านี้เป็นจริงเสมอ
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

คืนค่า cell พาเรนท์หรือ null หากออบเจกต์พาเรนท์ไม่ได้ทำตามอินเทอร์เฟซ ICell อ่านอย่างเดียว [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // การยืนยันเหล่านี้เป็นจริงเสมอ
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**ผลลัพธ์:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

รวม run ที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการไฮไลท์ |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

แบ่งเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาเรย์ของสตริง โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกต่างหากภายในกรอบ

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // รับ shape แรกบนสไลด์และแคสต์เป็น ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // แบ่งเนื้อหา text frame เป็นคอลัมน์
>      String[] columnsText = textFrame.splitTextByColumns();
>      // พิมพ์ข้อความของแต่ละคอลัมน์ไปที่คอนโซล
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ผลลัพธ์:**
java.lang.String[] - อาเรย์ของสตริง โดยแต่ละสตริงแทนเนื้อหาข้อความของคอลัมน์เฉพาะใน [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

หาก TextFrame ไม่มีหลายคอลัมน์ อาเรย์ที่คืนค่าจะมีองค์ประกอบเดียวที่มีข้อความทั้งหมด คอลัมน์ที่ว่างจะถูกแทนที่ด้วยสตริงว่างในอาเรย์
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

ไฮไลท์ทุกตำแหน่งที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการไฮไลท์ |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการไฮไลท์ |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
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
>      // ไฮไลท์การปรากฏของ 'the' แยกต่างหากทั้งหมด
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจกต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

ไฮไลท์ทุกตำแหน่งที่ตรงกับนิพจน์ประจำด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // ไฮไลท์คำทั้งหมดที่มีอักขระ 5 ตัวหรือมากกว่า
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ประจำ java.util.regex.Pattern เพื่อดึงสตริงที่ต้องการไฮไลท์ |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจกต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

ไฮไลท์ทุกตำแหน่งที่ตรงกับนิพจน์ประจำด้วยสีที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.lang.String | ข้อความของนิพจน์ประจำเพื่อดึงข้อความที่ต้องการไฮไลท์ |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการไฮไลท์ |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การปรากฏของ 'the' แยกต่างหากทั้งหมดด้วย '***'
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
| newText | java.lang.String | สตริงที่จะใช้แทนที่ทุกการปรากฏของ oldText |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจกต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

แทนที่ทุกตำแหน่งที่ตรงกับนิพจน์ประจำด้วยสตริงที่ระบุ.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // แทนที่คำทั้งหมดที่มีสัญลักษณ์ 5 ตัวหรือมากกว่าด้วย '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ประจำ java.util.regex.Pattern เพื่อดึงสตริงที่ต้องการแทนที่ |
| newText | java.lang.String | สตริงที่จะใช้แทนที่ทุกการปรากฏของสตริงที่ต้องการแทนที่ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจกต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback).