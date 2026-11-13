---
title: ITextFrame
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึง TextFrame.
type: docs
url: /th/com.aspose.slides/itextframe/
---
**ทั้งหมดที่นำไปใช้ในอินเทอร์เฟซ:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

แสดงถึง TextFrame.
## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | ส่งกลับรายการของย่อหน้าทั้งหมดในเฟรม |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame |
| [getTextFrameFormat()](#getTextFrameFormat--) | ส่งกลับออบเจกต์การจัดรูปแบบสำหรับ TextFrame นี้ |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงไฮเปอร์ลิงก์ที่ประกอบอยู่ได้อย่างง่ายดาย |
| [getParentShape()](#getParentShape--) | ส่งกลับรูปร่างแม่หรือ null หากออบเจกต์แม่ไม่ได้ทำตามอินเทอร์เฟซ IShape อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape) |
| [getTextRect()](#getTextRect--) | รับสี่เหลี่ยมข้อความที่กำหนดโดยเรขาคณิตของรูปร่างแม่ |
| [getParentCell()](#getParentCell--) | ส่งกลับเซลล์แม่หรือ null หากออบเจกต์แม่ไม่ได้ทำตามอินเทอร์เฟซ ICell |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ |
| [splitTextByColumns()](#splitTextByColumns--) | แบ่งเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาร์เรย์ของสตริง โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกภายในเฟรม |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | ไฮไลต์ทุกการจับคู่ของนิพจน์ทั่วไปด้วยสีที่ระบุ |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | ไฮไลต์ทุกการจับคู่ของนิพจน์ทั่วไปด้วยสีที่ระบุ |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความที่ระบุอื่น |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการจับคู่ของนิพจน์ทั่วไปด้วยสตริงที่ระบุ |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

ส่งกลับรายการของย่อหน้าทั้งหมดในเฟรม อ่านอย่างเดียว [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**ผลลัพธ์:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame อ่าน/เขียน String.

ค่า: ข้อความ.

**ผลลัพธ์:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

รับหรือกำหนดข้อความธรรมดาสำหรับ TextFrame อ่าน/เขียน String.

ค่า: ข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

ส่งกลับออบเจกต์การจัดรูปแบบสำหรับ TextFrame นี้ อ่านอย่างเดียว [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**ผลลัพธ์:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงไฮเปอร์ลิงก์ที่ประกอบอยู่ได้อย่างง่ายดาย อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**ผลลัพธ์:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

ส่งกลับรูปร่างแม่หรือ null หากออบเจกต์แม่ไม่ได้ทำตามอินเทอร์เฟซ IShape อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

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


**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape)

### getTextRect() {#getTextRect--}
```
public abstract Rectangle2D.Float getTextRect()
```

รับสี่เหลี่ยมข้อความที่กำหนดโดยเรขาคณิตของรูปร่างแม่.

**ผลลัพธ์:**
java.awt.geom.Rectangle2D.Float - A java.awt.geom.Rectangle2D.Float that defines the text area.

--------------------

พิกัดสี่เหลี่ยมมาจากมุมบนซ้ายของรูปร่างแม่
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

ส่งกลับเซลล์แม่หรือ null หากออบเจกต์แม่ไม่ได้ทำตามอินเทอร์เฟซ ICell อ่านอย่างเดียว [ICell](../../com.aspose.slides/icell).

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


**ผลลัพธ์:**
[ICell](../../com.aspose.slides/icell)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

รวมรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมด.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะไฮไลต์ |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

แบ่งเนื้อหาข้อความของ [ITextFrame](../../com.aspose.slides/itextframe) เป็นอาร์เรย์ของสตริง โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกภายในเฟรม.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // รับรูปทรงแรกบนสไลด์และแปลงเป็น ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // แบ่งเนื้อหาเฟรมข้อความเป็นคอลัมน์
>      String[] columnsText = textFrame.splitTextByColumns();
>      // พิมพ์ข้อความของแต่ละคอลัมน์ลงคอนโซล
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ผลลัพธ์:**
java.lang.String[] - อาร์เรย์ของสตริง โดยแต่ละสตริงแทนเนื้อหาข้อความของคอลัมน์เฉพาะใน [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

หาก TextFrame ไม่ประกอบด้วยหลายคอลัมน์ อาร์เรย์ที่ส่งกลับจะมีเพียงหนึ่งองค์ประกอบที่บรรจุข้อความทั้งหมด คอลัมน์ที่ว่างจะถูกแสดงเป็นสตริงเปล่าในอาร์เรย์
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะไฮไลต์ |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการไฮไลต์ |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ.

--------------------

> ```
> ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลต์ข้อความใน TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // ไฮไลต์คำทั้งหมด 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // ไฮไลต์การปรากฏตัวของ 'the' แยกแต่ละคำ
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะไฮไลต์ |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | ออบเจกต์คอลแบ็ครับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

ไฮไลต์ทุกการจับคู่ของนิพจน์ทั่วไปด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // ไฮไลต์คำทั้งหมดที่มี 5 ตัวอักษรหรือมากกว่า
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ทั่วไป java.util.regex.Pattern เพื่อรับสตริงที่จะไฮไลต์ |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | ออบเจกต์คอลแบ็ครับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

ไฮไลต์ทุกการจับคู่ของนิพจน์ทั่วไปด้วยสีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| regex | java.lang.String | ข้อความของนิพจน์ทั่วไปเพื่อรับข้อความที่ต้องการไฮไลต์ |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลต์ข้อความ |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ตัวเลือกการไฮไลต์ |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความที่ระบุอื่น.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การปรากฏของ 'the' ที่แยกกันทั้งหมดด้วย '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| oldText | java.lang.String | สตริงที่จะถูกแทนที่ |
| newText | java.lang.String | สตริงที่จะใช้แทนที่ทุกการปรากฏของ oldText |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | ออบเจกต์คอลแบ็ครับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

แทนที่ทุกการจับคู่ของนิพจน์ทั่วไปด้วยสตริงที่ระบุ.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // แทนที่คำทั้งหมดที่มี 5 สัญลักษณ์หรือยาวกว่าเป็น '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ทั่วไป java.util.regex.Pattern เพื่อรับสตริงที่จะแทนที่ |
| newText | java.lang.String | สตริงที่จะใช้แทนที่ทุกการปรากฏของสตริงที่ต้องการแทนที่ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | ออบเจกต์คอลแบ็ครับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |