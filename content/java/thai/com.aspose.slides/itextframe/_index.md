---
title: ITextFrame
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
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
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | ส่งคืนรายการของย่อหน้าทั้งหมดในเฟรมหนึ่ง. |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | ส่งคืนอ็อบเจ็กต์การจัดรูปแบบสำหรับอ็อบเจ็กต์ TextFrame นี้. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย. |
| [getParentShape()](#getParentShape--) | ส่งคืนรูปร่างแม่หรือ null หากอ็อบเจ็กต์แม่ไม่ได้ทำการใช้งานอินเทอร์เฟซ IShape อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | ส่งคืนเซลล์แม่หรือ null หากอ็อบเจ็กต์แม่ไม่ได้ทำการใช้งานอินเทอร์เฟซ ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | เชื่อมส่วนที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้า. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่กำหนด. |
| [splitTextByColumns()](#splitTextByColumns--) | แยกเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาเรย์ของสตริง โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกต่างหากภายในเฟรม. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่กำหนด. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่กำหนด. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับนิพจน์ปกติกับสีที่กำหนด. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับนิพจน์ปกติกับสีที่กำหนด. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการพบของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการพบของนิพจน์ปกติกับสตริงที่ระบุ. |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```


ส่งคืนรายการของย่อหน้าทั้งหมดในเฟรม. อ่านอย่างเดียว [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**ส่งคืน:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```


รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame. อ่าน/เขียน String.

ค่า: ข้อความ.

**ส่งคืน:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame. อ่าน/เขียน String.

ค่า: ข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```


ส่งคืนอ็อบเจ็กต์การจัดรูปแบบสำหรับอ็อบเจ็กต์ TextFrame นี้. อ่านอย่างเดียว [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**ส่งคืน:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย. อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**ส่งคืน:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```


ส่งคืนรูปร่างแม่หรือ null หากอ็อบเจ็กต์แม่ไม่ได้ทำการใช้งานอินเทอร์เฟซ IShape อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

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


**ส่งคืน:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```


ส่งคืนเซลล์แม่หรือ null หากอ็อบเจ็กต์แม่ไม่ได้ทำการใช้งานอินเทอร์เฟซ ICell. อ่านอย่างเดียว [ICell](../../com.aspose.slides/icell).

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


**ส่งคืน:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


เชื่อมส่วนที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้า.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```


ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการไฮไลต์. |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```


แยกเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาเรย์ของสตริง โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกต่างหากภายในเฟรม.

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการใช้ #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // ดึงรูปแบบแรกบนสไลด์และแปลงเป็น ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // แยกเนื้อหาของ TextFrame ไปเป็นคอลัมน์
>      String[] columnsText = textFrame.splitTextByColumns();
>      // พิมพ์ข้อความของแต่ละคอลัมน์ไปที่คอนโซล
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**
java.lang.String[] - อาเรย์ของสตริง โดยแต่ละสตริงแทนเนื้อหาข้อความของคอลัมน์เฉพาะใน [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

หาก TextFrame ไม่มีหลายคอลัมน์ อาเรย์ที่ส่งคืนจะมีเพียงองค์ประกอบเดียวที่บรรจุข้อความทั้งหมด คอลัมน์ที่ว่างจะถูกแสดงเป็นสตริงว่างในอาเรย์.
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```


ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการไฮไลต์. |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการไฮไลต์. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่กำหนด.

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
>      // ไฮไลท์การปรากฏของ 'the' ทุกอันแยกกัน
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการไฮไลต์. |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อมูล [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์คอลแบ็กสำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับนิพจน์ปกติกับสีที่กำหนด.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // การไฮไลท์คำทั้งหมดที่มี 5 สัญลักษณ์หรือยาวกว่า
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ปกติ java.util.regex.Pattern เพื่อรับสตริงที่ต้องการไฮไลต์. |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์คอลแบ็กสำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```


ทำไฮไลต์ให้กับทั้งหมดที่ตรงกับนิพจน์ปกติกับสีที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.lang.String | ข้อความของนิพจน์ปกติเพื่อรับข้อความที่ต้องการไฮไลต์. |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการไฮไลต์. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


แทนที่ทุกการพบของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่ทุกการปรากฏของ 'the' ที่แยกจากกันด้วย '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| oldText | java.lang.String | สตริงที่จะถูกแทนที่. |
| newText | java.lang.String | สตริงที่จะใช้แทนที่ทุกการปรากฏของ oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อมูล [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์คอลแบ็กสำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


แทนที่ทุกการพบของนิพจน์ปกติกับสตริงที่ระบุ.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // แทนที่คำทั้งหมดที่มี 5 สัญลักษณ์หรือยาวกว่า ด้วย '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ปกติ java.util.regex.Pattern เพื่อรับสตริงที่ต้องการแทนที่. |
| newText | java.lang.String | สตริงที่จะใช้แทนที่ทุกการปรากฏของสตริงที่ต้องการแทนที่. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์คอลแบ็กสำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |