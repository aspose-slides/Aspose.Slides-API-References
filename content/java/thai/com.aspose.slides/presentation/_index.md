---
title: Presentation
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นการนำเสนอ Microsoft PowerPoint.
type: docs
url: /th/com.aspose.slides/presentation/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

เป็นการนำเสนอ Microsoft PowerPoint

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // สร้างวัตถุ Presentation ที่เป็นตัวแทนของไฟล์การนำเสนอ
>  Presentation pres = new Presentation();
>  try {
>      // ดึงสไลด์แรก
>      ISlide slide = pres.getSlides().get_Item(0);
>      // เพิ่มรูปอัตโนมัติประเภทเส้น
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // บันทึกไฟล์การนำเสนอ
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // โหลดไฟล์ที่รองรับทั้งหมดใน Presentation เช่น ppt, pptx, odp เป็นต้น
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // บันทึกไฟล์การนำเสนอ
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## ตัวสร้าง

| ตัวสร้าง | รายละเอียด |
| --- | --- |
| [Presentation()](#Presentation--) | ตัวสร้างนี้สร้างการนำเสนอใหม่จากศูนย์ |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | ตัวสร้างนี้สร้างการนำเสนอใหม่จากศูนย์ |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่านการนำเสนอที่มีอยู่ |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่านการนำเสนอที่มีอยู่ |
| [Presentation(String file)](#Presentation-java.lang.String-) | ตัวสร้างนี้รับเส้นทางไฟล์ต้นทางที่ใช้สำหรับอ่านเนื้อหาของการนำเสนอ |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | ตัวสร้างนี้รับเส้นทางไฟล์ต้นทางที่ใช้สำหรับอ่านเนื้อหาของการนำเสนอ |

## วิธีการ

| วิธีการ | รายละเอียด |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | คืนค่า หรือ ตั้งค่าวันที่และเวลาที่จะแทนที่เนื้อหาของฟิลด์ datetime |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | คืนค่า หรือ ตั้งค่าวันที่และเวลาที่จะแทนที่เนื้อหาของฟิลด์ datetime |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนผู้จัดการ HeaderFooter ปัจจุบัน |
| [getProtectionManager()](#getProtectionManager--) | รับผู้จัดการสิทธิ์สำหรับการนำเสนอนี้ |
| [getSlides()](#getSlides--) | คืนรายการสไลด์ทั้งหมดที่กำหนดในการนำเสนอ |
| [getSections()](#getSections--) | คืนรายการส่วนของสไลด์ทั้งหมดที่กำหนดในการนำเสนอ |
| [getSlideSize()](#getSlideSize--) | คืนอ็อบเจ็กต์ขนาดสไลด์ |
| [getNotesSize()](#getNotesSize--) | คืนอ็อบเจ็กต์ขนาดสไลด์โน้ต |
| [getLayoutSlides()](#getLayoutSlides--) | คืนรายการสไลด์เค้าโครงทั้งหมดที่กำหนดในการนำเสนอ |
| [getMasters()](#getMasters--) | คืนรายการสไลด์มาสเตอร์ทั้งหมดที่กำหนดในการนำเสนอ |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | คืนผู้จัดการโน้ตมาสเตอร์ |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | คืนผู้จัดการแฮนด์เอาท์มาสเตอร์ |
| [getFontsManager()](#getFontsManager--) | คืนผู้จัดการฟอนต์ |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | คืนสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง |
| [getCommentAuthors()](#getCommentAuthors--) | คืนคอลเลกชันของผู้เขียนความคิดเห็น |
| [getDocumentProperties()](#getDocumentProperties--) | คืนอ็อบเจ็กต์ DocumentProperties ซึ่งมีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร |
| [getImages()](#getImages--) | คืนคอลเลกชันของรูปภาพทั้งหมดในการนำเสนอ |
| [getAudios()](#getAudios--) | คืนคอลเลกชันของไฟล์เสียงฝังทั้งหมดในการนำเสนอ |
| [getVideos()](#getVideos--) | คืนคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในการนำเสนอ |
| [getSlideShowSettings()](#getSlideShowSettings--) | คืนการตั้งค่าสไลด์โชว์สำหรับการนำเสนอ |
| [getDigitalSignatures()](#getDigitalSignatures--) | คืนคอลเลกชันของลายเซ็นที่ใช้ลงนามการนำเสนอ |
| [getCustomData()](#getCustomData--) | คืนข้อมูลกำหนดเองของการนำเสนอ |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | คืนส่วนข้อมูลกำหนดเองทั้งหมดในการนำเสนอ |
| [getVbaProject()](#getVbaProject--) | รับหรือกำหนดโครงการ VBA พร้อมแมโครการนำเสนอ |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | รับหรือกำหนดโครงการ VBA พร้อมแมโครการนำเสนอ |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์การนำเสนอทั้งหมดอย่างง่าย (ไม่รวมในสไลด์มาสเตอร์, เค้าโครง, โน้ต) |
| [getViewProperties()](#getViewProperties--) | รับคุณสมบัตุมุมมองทั่วทั้งการนำเสนอ |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [getSensitivityLabels()](#getSensitivityLabels--) | คืนคอลเลกชันของป้ายกำกับความอ่อนไหวที่ใช้กับเอกสารการนำเสนอ |
| [getSlideById(long id)](#getSlideById-long-) | คืน Slide, MasterSlide หรือ LayoutSlide ตาม Id |
| [getSourceFormat()](#getSourceFormat--) | คืนข้อมูลเกี่ยวกับรูปแบบที่การนำเสนอโหลดมาจาก |
| [getMasterTheme()](#getMasterTheme--) | คืนธีมมาสเตอร์ |
| [save(String fname, int format)](#save-java.lang.String-int-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นสตรีมในรูปแบบที่ระบุ |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นสตรีมในรูปแบบที่ระบุและตัวเลือกเพิ่มเติม |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่เป็นเครื่องหมาย XAML |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | คืนอ็อบเจ็กต์ Image สำหรับสไลด์ทั้งหมดของการนำเสนอ |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | คืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอ |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | คืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอพร้อมการปรับสเกลที่กำหนดเอง |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | คืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอพร้อมการปรับสเกลที่กำหนดเอง |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | คืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยขนาดที่ระบุ |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | คืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยขนาดที่กำหนด |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุโดยคงหมายเลขหน้า |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุโดยคงหมายเลขหน้าและตัวเลือกการบันทึกเพิ่มเติม |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นสตรีมในรูปแบบที่ระบุโดยคงหมายเลขหน้า |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นสตรีมในรูปแบบที่ระบุโดยคงหมายเลขหน้าและตัวเลือกการบันทึกเพิ่มเติม |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับได้ทั้งหมดในสไลด์ทั้งหมด |
| [dispose()](#dispose--) | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจ็กต์ Presentation นี้ |
| [getPresentation()](#getPresentation--) | คืนการนำเสนอพาเรนต์ของข้อความ |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | ไฮไลท์การจับคู่ทั้งหมดของ regular expression ด้วยสีที่ระบุ |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการพบของข้อความที่ระบุด้วยข้อความที่ระบุอื่น |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่การจับคู่ทั้งหมดของ regular expression ด้วยสตริงที่ระบุ |

### Presentation() {#Presentation--}
```
public Presentation()
```

ตัวสร้างนี้สร้างการนำเสนอใหม่จากศูนย์ การนำเสนอที่สร้างมีสไลด์เปล่าหนึ่งสไลด์

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

ตัวสร้างนี้สร้างการนำเสนอใหม่จากศูนย์ การนำเสนอที่สร้างมีสไลด์เปล่าหนึ่งสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | ตัวเลือกการโหลดเพิ่มเติม |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่านการนำเสนอที่มีอยู่

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมอินพุต |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่านการนำเสนอที่มีอยู่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมอินพุต |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | ตัวเลือกการโหลดเพิ่มเติม |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

ตัวสร้างนี้รับเส้นทางไฟล์ต้นทางที่ใช้สำหรับอ่านเนื้อหาของการนำเสนอ

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์อินพุต |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

ตัวสร้างนี้รับเส้นทางไฟล์ต้นทางที่ใช้สำหรับอ่านเนื้อหาของการนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์อินพุต |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | ตัวเลือกการโหลดเพิ่มเติม |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

คืนค่า หรือ ตั้งค่าวันที่และเวลาที่จะแทนที่เนื้อหาของฟิลด์ datetime เวลาเพิ่มเติมเป็นเวลาการสร้างอ็อบเจ็กต์ Presentation นี้โดยค่าเริ่มต้น อ่าน/เขียน java.util.Date

**คืนค่า:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

คืนค่า หรือ ตั้งค่าวันที่และเวลาที่จะแทนที่เนื้อหาของฟิลด์ datetime เวลาเพิ่มเติมเป็นเวลาการสร้างอ็อบเจ็กต์ Presentation นี้โดยค่าเริ่มต้น อ่าน/เขียน java.util.Date

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว IDOMObject

**คืนค่า:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

คืนผู้จัดการ HeaderFooter ปัจจุบัน อ่านอย่างเดียว [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible ใช้บ่งชี้ว่าตัวล็อกเทมเพลตส่วนล่างของสไลด์ไม่มีอยู่
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility ใช้ทำให้ตัวล็อกเทมเพลตส่วนล่างของสไลด์ปรากฏ
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible ใช้บ่งชี้ว่าตัวล็อกเทมเพลตเลขหน้าของสไลด์ไม่มีอยู่
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility ใช้ทำให้ตัวล็อกเทมเพลตเลขหน้าของสไลด์ปรากฏ
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible ใช้บ่งชี้ว่าตัวล็อกเทมเพลตวันที่-เวลาในสไลด์ไม่มีอยู่
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility ใช้ทำให้ตัวล็อกเทมเพลตวันที่-เวลาในสไลด์ปรากฏ
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText ใช้ตั้งค่าข้อความให้กับตัวล็อกเทมเพลตส่วนล่างของสไลด์
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText ใช้ตั้งค่าข้อความให้กับตัวล็อกเทมเพลตวันที่-เวลาในสไลด์
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility ใช้ทำให้สไลด์แม่และตัวล็อกเทมเพลตส่วนล่างของลูกทั้งหมดปรากฏ
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility ใช้ทำให้สไลด์แม่และตัวล็อกเทมเพลตเลขหน้าของลูกทั้งหมดปรากฏ
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility ใช้ทำให้สไลด์แม่และตัวล็อกเทมเพลตวันที่-เวลาของลูกทั้งหมดปรากฏ
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText ใช้ตั้งค่าข้อความให้กับสไลด์แม่และตัวล็อกเทมเพลตส่วนล่างของลูกทั้งหมด
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText ใช้ตั้งค่าข้อความให้กับสไลด์แม่และตัวล็อกเทมเพลตวันที่-เวลาของลูกทั้งหมด
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

รับผู้จัดการสิทธิ์สำหรับการนำเสนอนี้ อ่านอย่างเดียว [IProtectionManager](../../com.aspose.slides/iprotectionmanager)

**คืนค่า:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

คืนรายการสไลด์ทั้งหมดที่กำหนดในการนำเสนอ อ่านอย่างเดียว [ISlideCollection](../../com.aspose.slides/islidecollection)

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the first ISlide to Blue
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Set the background with Image
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Set the picture
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Add image to presentation's images collection
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Write the presentation to disk
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Write the presentation to disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instantiate Presentation class that represents a presentation file
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Set the transition time of 3 seconds
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Set the transition time of 5 seconds
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Apply zoom type transition on slide 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Set the transition time of 7 seconds
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Write the presentation to disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

คืนรายการส่วนของสไลด์ทั้งหมดที่กำหนดในการนำเสนอ อ่านอย่างเดียว [ISectionCollection](../../com.aspose.slides/isectioncollection)

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 จะสิ้นสุดที่ newSlide2 และหลังจากนั้น section2 จะเริ่มต้น
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

คืนอ็อบเจ็กต์ขนาดสไลด์ อ่านอย่างเดียว [ISlideSize](../../com.aspose.slides/islidesize)

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Set the slide size of generated presentations to that of source
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Method SetSize is used for set slide size with scale content to ensure fit
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Method SetSize is used for set slide size with maximize size of content
>          // Save Presentation to disk
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 paper size
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

คืนอ็อบเจ็กต์ขนาดสไลด์โน้ต อ่านอย่างเดียว [INotesSize](../../com.aspose.slides/inotessize)

**คืนค่า:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

คืนรายการสไลด์เค้าโครงทั้งหมดที่กำหนดในการนำเสนอ อ่านอย่างเดียว [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

--------------------

คุณสามารถเข้าถึง API ทางเลือกสำหรับการเพิ่ม/แทรก/ลบ/คัดลอกสไลด์เค้าโครงโดยใช้คุณสมบัติ IMasterSlide.LayoutSlides

**คืนค่า:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

คืนรายการสไลด์มาสเตอร์ทั้งหมดที่กำหนดในการนำเสนอ อ่านอย่างเดียว [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the Master ISlide to Forest Green
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Write the presentation to disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Try to search by layout slide type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // The situation when a presentation doesn't contain some type of layouts.
>          // presentation File only contains Blank and Custom layout types.
>          // But layout slides with Custom types has different slide names,
>          // like "Title", "Title and Content", etc. And it is possible to use these
>          // names for layout slide selection.
>          // Also it is possible to use the set of placeholder shape types. For example,
>          // Title slide should have only Title pleceholder type, etc.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Adding empty slide with added layout slide
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Save presentation
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

คืนผู้จัดการโน้ตมาสเตอร์ อ่านอย่างเดียว [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

**คืนค่า:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

คืนผู้จัดการแฮนด์เอาท์มาสเตอร์ อ่านอย่างเดียว [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

**คืนค่า:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

คืนผู้จัดการฟอนต์ อ่านอย่างเดียว [IFontsManager](../../com.aspose.slides/ifontsmanager)

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Load presentation
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Load source font to be replaced
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Save the presentation
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

คืนสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle)

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

คืนคอลเลกชันของผู้เขียนความคิดเห็น อ่านอย่างเดียว [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

**คืนค่า:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

คืนอ็อบเจ็กต์ DocumentProperties ซึ่งมีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร อ่านอย่างเดียว [IDocumentProperties](../../com.aspose.slides/idocumentproperties)

**คืนค่า:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

คืนคอลเลกชันของรูปภาพทั้งหมดในการนำเสนอ อ่านอย่างเดียว [IImageCollection](../../com.aspose.slides/iimagecollection)

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // creates a new presentation to which the image will be added.
>  Presentation pres = new Presentation();
>  try
>  {
>      // supposed we have the large image file we want to include into the presentation
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Let's add the image to the presentation - we choose KeepLocked behavior because we do
>          // NOT intend to access the "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Adds image to presentation
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Creates picture frame on slide 1 based on previously added image
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

คืนคอลเลกชันของไฟล์เสียงฝังทั้งหมดในการนำเสนอ อ่านอย่างเดียว [IAudioCollection](../../com.aspose.slides/iaudiocollection)

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
คืนคอลเลกชันของไฟล์วิดีโอที่ฝังอยู่ทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**  
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

คืนค่าการตั้งค่าแสดงสไลด์สำหรับงานนำเสนอ.

**คืนค่า:**  
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

คืนคอลเลกชันของลายเซ็นที่ใช้เพื่อเซ็นงานนำเสนอ. อ่านอย่างเดียว [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**  
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

คืนข้อมูลกำหนดเองของงานนำเสนอ. อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**คืนค่า:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

คืนส่วนข้อมูล XML กำหนดเองทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // วนลูปทุกส่วน XML แบบกำหนดเอง
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**  
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

รับหรือกำหนดโปรเจกต์ VBA พร้อมแมโครของงานนำเสนอ. อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject).

**คืนค่า:**  
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

รับหรือกำหนดโปรเจกต์ VBA พร้อมแมโครของงานนำเสนอ. อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงง่ายต่อไฮเปอร์ลิงก์ทั้งหมดที่อยู่ในสไลด์ของงานนำเสนอ (ไม่รวมมาสเตอร์, เลย์เอาต์, สไลด์โน้ต). อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**คืนค่า:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

รับคุณสมบัติวิวระดับงานนำเสนอ. อ่านอย่างเดียว [IViewProperties](../../com.aspose.slides/iviewproperties).

**คืนค่า:**  
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

แสดงหมายเลขสไลด์แรกในงานนำเสนอ

**คืนค่า:**  
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

แสดงหมายเลขสไลด์แรกในงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

คืนคอลเลกชันของป้ายความอ่อนไหวที่ใช้กับเอกสารงานนำเสนอ. อ่านอย่างเดียว [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // แสดงป้ายกำกับที่ใช้
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // เพิ่มป้ายกำกับใหม่
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // ดึง Id ของป้ายความอ่อนไหวงจากนโยบาย
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // ดึงตัวระบุไซต์ Azure AD จากนโยบาย
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**  
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

คืนค่า Slide, MasterSlide หรือ LayoutSlide ตาม Id.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | long | Id ของสไลด์. |

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

คืนข้อมูลเกี่ยวกับรูปแบบที่งานนำเสนอถูกโหลด. อ่านอย่างเดียว [SourceFormat](../../com.aspose.slides/sourceformat).

**คืนค่า:**  
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

คืนธีมหลัก. อ่านอย่างเดียว [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // สร้างอ็อบเจกต์ Presentation ที่แทนไฟล์การนำเสนอ
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**  
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงไฟล์ด้วยรูปแบบที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงสตรีมด้วยรูปแบบที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงไฟล์ด้วยรูปแบบที่กำหนดและด้วยตัวเลือกเพิ่มเติม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงสตรีมด้วยรูปแบบที่กำหนดและด้วยตัวเลือกเพิ่มเติม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่เป็นมาร์คอัป XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | ตัวเลือกรูปแบบ XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

คืนอ็อบเจกต์ Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |

**คืนค่า:**  
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งสไลด์, เริ่มจาก 1. |

**คืนค่า:**  
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยการสเกลที่กำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| scaleX | float | ค่าที่ใช้เพื่อสเกล Thumbnail นี้ในทิศทางแกน x. |
| scaleY | float | ค่าที่ใช้เพื่อสเกล Thumbnail นี้ในทิศทางแกน y. |

**คืนค่า:**  
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยการสเกลที่กำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งสไลด์, เริ่มจาก 1. |
| scaleX | float | ค่าที่ใช้เพื่อสเกล Thumbnail นี้ในทิศทางแกน x. |
| scaleY | float | ค่าที่ใช้เพื่อสเกล Thumbnail นี้ในทิศทางแกน y. |

**คืนค่า:**  
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยขนาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| imageSize | java.awt.Dimension | ขนาดของรูปภาพที่จะสร้าง. |

**คืนค่า:**  
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยขนาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งสไลด์, เริ่มจาก 1. |
| imageSize | java.awt.Dimension | ขนาดของรูปภาพที่จะสร้าง. |

**คืนค่า:**  
com.aspose.slides.IImage[] - Image objects.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของงานนำเสนอลงไฟล์ด้วยรูปแบบที่กำหนดโดยคงหมายเลขหน้า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง. |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งสไลด์, เริ่มจาก 1. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของงานนำเสนอลงไฟล์ด้วยรูปแบบที่กำหนดโดยคงหมายเลขหน้า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง. |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งสไลด์, เริ่มจาก 1. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของงานนำเสนอลงสตรีมด้วยรูปแบบที่กำหนดโดยคงหมายเลขหน้า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต. |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งสไลด์, เริ่มจาก 1. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของงานนำเสนอลงสตรีมด้วยรูปแบบที่กำหนดโดยคงหมายเลขหน้า.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต. |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งสไลด์, เริ่มจาก 1. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับในทุกสไลด์.

### dispose() {#dispose--}
```
public final void dispose()
```

ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจกต์ Presentation นี้.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนงานนำเสนอแม่ของข้อความ. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // ไฮไลท์ทุกการเกิดของคำ 'the' ที่แยกออกจากกัน
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะทำการไฮไลท์. |
| highlightColor | java.awt.Color | สีที่จะใช้ไฮไลท์ข้อความ. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // highlighting all separate 'the' occurrences
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะทำการไฮไลท์. |
| highlightColor | java.awt.Color | สีที่จะใช้ไฮไลท์ข้อความ. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจกต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

ไฮไลท์การจับคู่ทั้งหมดของนิพจน์ปกติด้วยสีที่ระบุ.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // ไฮไลท์คำทั้งหมดที่มีสัญลักษณ์ 10 ตัวหรือมากกว่า
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ปกติ java.util.regex.Pattern เพื่อรับสตริงที่จะทำการไฮไลท์. |
| highlightColor | java.awt.Color | สีที่จะใช้ไฮไลท์ข้อความ. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจกต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

แทนที่ข้อความที่ระบุทั้งหมดด้วยข้อความอื่นที่ระบุ

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่ทุกการเกิดของคำ 'the' ที่แยกออกจากกันด้วย '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| oldText | java.lang.String | สตริงที่ต้องการแทนที่ |
| newText | java.lang.String | สตริงที่จะใช้แทนที่ทุกการปรากฏของ oldText |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

แทนที่ทุกการจับคู่ของนิพจน์ทั่วไปด้วยสตริงที่ระบุ

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // แทนที่คำทั้งหมดที่มีสัญลักษณ์ 10 ตัวหรือมากกว่าเป็น '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ทั่วไป java.util.regex.Pattern ที่ใช้เพื่อรับสตริงที่จะทำการแทนที่ |
| newText | java.lang.String | สตริงที่จะใช้แทนที่ทุกการปรากฏของสตริงที่ต้องการแทนที่ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |