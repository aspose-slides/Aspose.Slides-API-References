---
title: TextFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึง TextFrame.
type: docs
url: /th/com.aspose.slides/textframe/
---
**สืบทอด:**  
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการ Implement:**  
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject  
```
public final class TextFrame implements ITextFrame, IDOMObject
```

แสดงถึง TextFrame.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | ส่งคืนรายการของย่อหน้าทั้งหมดในเฟรมหนึ่ง |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame |
| [getTextFrameFormat()](#getTextFrameFormat--) | ส่งคืนวัตถุการจัดรูปแบบสำหรับวัตถุ TextFrame นี้ |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึง hyperlinks ที่รวมอยู่ได้อย่างง่าย |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวม runs ที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | เน้นสีทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | เน้นสีทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [splitTextByColumns()](#splitTextByColumns--) | แยกเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาร์เรย์ของสตริง, โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกภายในเฟรม |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | เน้นสีทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | เน้นสีทั้งหมดที่ตรงกับ regular expression ด้วยสีที่ระบุ |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | เน้นสีทั้งหมดที่ตรงกับ regular expression ด้วยสีที่ระบุ |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่การเกิดทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่การตรงทั้งหมดของ regular expression ด้วยสตริงที่ระบุ |
| [getSlide()](#getSlide--) | ส่งคืนสไลด์แม่ของ TextFrame |
| [getPresentation()](#getPresentation--) | ส่งคืนการนำเสนอแม่ของ TextFrame |
| [getParentShape()](#getParentShape--) | ส่งคืนรูปร่างแม่หรือ null หากวัตถุแม่ไม่ได้ implement อินเทอร์เฟซ IShape อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape) |
| [getParentCell()](#getParentCell--) | ส่งคืนเซลล์แม่หรือ null หากวัตถุแม่ไม่ได้ implement อินเทอร์เฟซ ICell อ่านอย่างเดียว |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนวัตถุ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ส่งคืน:**  
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

ส่งคืนรายการของย่อหน้าทั้งหมดในเฟรมหนึ่ง. อ่านอย่างเดียว [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**ส่งคืน:**  
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame. อ่าน/เขียน String.

ค่า: ข้อความ.

**ส่งคืน:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame. อ่าน/เขียน String.

ค่า: ข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

ส่งคืนวัตถุการจัดรูปแบบสำหรับวัตถุ TextFrame นี้. อ่านอย่างเดียว [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**ส่งคืน:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึง hyperlinks ที่รวมอยู่ได้อย่างง่าย. อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**ส่งคืน:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

รวม runs ที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

เน้นสีทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความตัวอย่างที่ต้องการเน้น |
| highlightColor | java.awt.Color | สีที่ใช้เน้นข้อความ |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

เน้นสีทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // ไฮไลท์ทุกคำ 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // ไฮไลท์ทุกการปรากฏของ 'the' แยกกัน
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการเน้น |
| highlightColor | java.awt.Color | สีที่ใช้เน้นข้อความ |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการเน้นสี |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

แยกเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาร์เรย์ของสตริง, โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกภายในเฟรม.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // รับรูปร่างแรกบนสไลด์และแคสต์เป็น ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // แยกเนื้อหา TextFrame ออกเป็นคอลัมน์
>      String[] columnsText = textFrame.splitTextByColumns();
>      // พิมพ์ข้อความของแต่ละคอลัมน์ไปที่คอนโซล
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**  
java.lang.String[] - อาเรย์ของสตริง, โดยแต่ละสตริงแทนเนื้อหาข้อความของคอลัมน์เฉพาะใน [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

หาก TextFrame ไม่มีหลายคอลัมน์, อาเรย์ที่ส่งกลับจะมีเพียงองค์ประกอบเดียวที่มีข้อความเต็ม. คอลัมน์ว่างจะถูกแทนด้วยสตริงว่างในอาเรย์.

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

เน้นสีทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // ไฮไลท์ทุกคำ 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // ไฮไลท์ทุกการปรากฏของ 'the' แยกกัน
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการเน้น |
| highlightColor | java.awt.Color | สีที่ใช้เน้นข้อความ |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

เน้นสีทั้งหมดที่ตรงกับ regular expression ด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // ไฮไลท์ทุกคำที่มีความยาว 10 สัญลักษณ์หรือมากกว่า
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.lang.String | ข้อความ regular expression เพื่อรับข้อความที่ต้องการเน้น |
| highlightColor | java.awt.Color | สีที่ใช้เน้นข้อความ |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการเน้นสี |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

เน้นสีทั้งหมดที่ตรงกับ regular expression ด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // ไฮไลท์ทุกคำที่มีความยาว 5 สัญลักษณ์หรือมากกว่า
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regular expression java.util.regex.Pattern เพื่อรับสตริงที่ต้องการเน้น |
| highlightColor | java.awt.Color | สีที่ใช้เน้นข้อความ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

แทนที่การเกิดทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การปรากฏทั้งหมดของ 'the' แยกกันด้วย '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| oldText | java.lang.String | สตริงที่ต้องการแทนที่ |
| newText | java.lang.String | สตริงที่จะใช้แทนที่การเกิดทั้งหมดของ oldText |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับบันทึกผลการดำเนินการแทนที่ [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

แทนที่การตรงทั้งหมดของ regular expression ด้วยสตริงที่ระบุ.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // แทนที่ทุกคำที่มีความยาว 5 สัญลักษณ์หรือมากกว่า ด้วย '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regular expression java.util.regex.Pattern เพื่อรับสตริงที่ต้องการแทนที่ |
| newText | java.lang.String | สตริงที่จะใช้แทนที่การเกิดทั้งหมดของสตริงที่ต้องการแทนที่ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับบันทึกผลการดำเนินการแทนที่ [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งคืนสไลด์แม่ของ TextFrame. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**ส่งคืน:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนการนำเสนอแม่ของ TextFrame. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ส่งคืน:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

ส่งคืนรูปร่างแม่หรือ null หากวัตถุแม่ไม่ได้ implement อินเทอร์เฟซ IShape อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // การอ้างอิงเหล่านี้เป็นจริงเสมอ
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
public final ICell getParentCell()
```

ส่งคืนเซลล์แม่หรือ null หากวัตถุแม่ไม่ได้ implement อินเทอร์เฟซ ICell อ่านอย่างเดียว [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // การอ้างอิงเหล่านี้เป็นจริงเสมอ
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**ส่งคืน:**  
[ICell](../../com.aspose.slides/icell)