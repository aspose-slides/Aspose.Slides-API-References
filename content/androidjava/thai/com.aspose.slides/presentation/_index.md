---
title: Presentation
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: เป็นตัวแทนของงานนำเสนอ Microsoft PowerPoint.
type: docs
url: /th/com.aspose.slides/presentation/
---
**สืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject  
```
public final class Presentation implements IPresentation, IDOMObject
```

เป็นตัวแทนของงานนำเสนอ Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation pres = new Presentation();
>  try {
>      // ดึงสไลด์แรก
>      ISlide slide = pres.getSlides().get_Item(0);
>      // เพิ่ม AutoShape ประเภทเส้น
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // บันทึกไฟล์งานนำเสนอ
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // โหลดไฟล์ที่รองรับใด ๆ ใน Presentation เช่น ppt, pptx, odp ฯลฯ
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // บันทึกไฟล์งานนำเสนอ
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [Presentation()](#Presentation--) | ตัวสร้างนี้สร้างงานนำเสนอใหม่จากศูนย์. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | ตัวสร้างนี้สร้างงานนำเสนอใหม่จากศูนย์. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่านงานนำเสนอที่มีอยู่. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่านงานนำเสนอที่มีอยู่. |
| [Presentation(String file)](#Presentation-java.lang.String-) | ตัวสร้างนี้รับเส้นทางไฟล์ต้นฉบับที่ใช้อ่านเนื้อหาของงานนำเสนอ. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | ตัวสร้างนี้รับเส้นทางไฟล์ต้นฉบับที่ใช้อ่านเนื้อหาของงานนำเสนอ. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | คืนค่า หรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาในฟิลด์วันที่และเวลา. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | คืนค่า หรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาในฟิลด์วันที่และเวลา. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ปัจจุบัน. |
| [getProtectionManager()](#getProtectionManager--) | รับ manager ของสิทธิ์สำหรับงานนำ้อนี้. |
| [getSlides()](#getSlides--) | คืนค่ารายการของสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. |
| [getSections()](#getSections--) | คืนค่ารายการของส่วนสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. |
| [getSlideSize()](#getSlideSize--) | คืนค่าอ็อบเจ็กต์ขนาดสไลด์. |
| [getNotesSize()](#getNotesSize--) | คืนค่าอ็อบเจ็กต์ขนาดสไลด์โน้ต. |
| [getLayoutSlides()](#getLayoutSlides--) | คืนค่ารายการของสไลด์เค้าโครงทั้งหมดที่กำหนดในงานนำเสนอ. |
| [getMasters()](#getMasters--) | คืนค่ารายการของสไลด์แม่ทั้งหมดที่กำหนดในงานนำเสนอ. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | คืนค่า notes master manager. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | คืนค่า handout master manager. |
| [getFontsManager()](#getFontsManager--) | คืนค่า fonts manager. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | คืนค่าสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง. |
| [getCommentAuthors()](#getCommentAuthors--) | คืนค่าคอลเลกชันของผู้เขียนความคิดเห็น. |
| [getDocumentProperties()](#getDocumentProperties--) | คืนค่าอ็อบเจ็กต์ DocumentProperties ที่มีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร. |
| [getImages()](#getImages--) | คืนค่าคอลเลกชันของภาพทั้งหมดในงานนำเสนอ. |
| [getAudios()](#getAudios--) | คืนค่าคอลเลกชันของไฟล์เสียงฝังทั้งหมดในงานนำเสนอ. |
| [getVideos()](#getVideos--) | คืนค่าคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในงานนำเสนอ. |
| [getSlideShowSettings()](#getSlideShowSettings--) | คืนค่าการตั้งค่าแสดงสไลด์โชว์ของงานนำเสนอ. |
| [getDigitalSignatures()](#getDigitalSignatures--) | คืนค่าคอลเลกชันของลายเซ็นที่ใช้เซ็นงานนำเสนอ. |
| [getCustomData()](#getCustomData--) | คืนค่าข้อมูลกำหนดเองของงานนำเสนอ. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | คืนค่าทุกส่วนข้อมูลกำหนดเองในงานนำเสนอ. |
| [getVbaProject()](#getVbaProject--) | รับหรือกำหนดโครงการ VBA ที่มีมาโครของงานนำเสนอ. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | รับหรือกำหนดโครงการ VBA ที่มีมาโครของงานนำเสนอ. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงอย่างง่ายต่อไฮเปอร์ลิงก์ทั้งหมดที่อยู่ในสไลด์ของงานนำเสนอ (ไม่รวมสไลด์แม่, เค้าโครง, โน้ต). |
| [getViewProperties()](#getViewProperties--) | รับคุณสมบัติการมองเห็นทั่วงานนำเสนอ. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | เป็นตัวแทนของหมายเลขสไลด์แรกในงานนำเสนอ |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | เป็นตัวแทนของหมายเลขสไลด์แรกในงานนำเสนอ |
| [getSensitivityLabels()](#getSensitivityLabels--) | คืนค่าคอลเลกชันของป้ายความอ่อนไหวที่ใช้กับเอกสารงานนำเสนอ. |
| [getSlideById(long id)](#getSlideById-long-) | คืนค่า Slide, MasterSlide หรือ LayoutSlide ตาม Id. |
| [getSourceFormat()](#getSourceFormat--) | คืนข้อมุลเกี่ยวกับรูปแบบที่งานนำมาโหลด. |
| [getMasterTheme()](#getMasterTheme--) | คืนค่า master theme. |
| [save(String fname, int format)](#save-java.lang.String-int-) | บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังไฟล์ในรูปแบบที่ระบุ. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุ. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังไฟล์ในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่เป็น XAML markup. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | คืนค่าอ็อบเจ็กต์ Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอ. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยการสเกลแบบกำหนดเอง. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยการสเกลแบบกำหนดเอง. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยขนาดที่ระบุ. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยขนาดที่ระบุ. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | บันทึกสไลด์ที่ระบุของงานนำเสนอไปยังไฟล์ในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ที่ระบุของงานนำเสนอไปยังไฟล์ในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | บันทึกสไลด์ที่ระบุของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ที่ระบุของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่รองรับทั้งหมดในทุกสไลด์. |
| [dispose()](#dispose--) | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจ็กต์ Presentation นี้. |
| [getPresentation()](#getPresentation--) | คืนค่า presentation พาเรนท์ของข้อความ. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | ไฮไลท์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่การเกิดขึ้นทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสตริงที่ระบุ. |

### Presentation() {#Presentation--}
```
public Presentation()
```

ตัวสร้างนี้สร้างงานนำเสนอใหม่จากศูนย์ งานนำเสนอที่สร้างมีสไลด์ว่างหนึ่งสไลด์.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

ตัวสร้างนี้สร้างงานนำเสนอใหม่จากศูนย์ งานนำเสนอที่สร้างมีสไลด์ว่างหนึ่งสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | ตัวเลือกการโหลดเพิ่มเติม. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่านงานนำเสนอที่มีอยู่.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมอินพุต. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่านงานนำเสนอที่มีอยู่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมอินพุต. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | ตัวเลือกการโหลดเพิ่มเติม. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

ตัวสร้างนี้รับเส้นทางไฟล์ต้นฉบับที่ใช้อ่านเนื้อหาของงานนำเสนอ.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์อินพุต. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

ตัวสร้างนี้รับเส้นทางไฟล์ต้นฉบับที่ใช้อ่านเนื้อหาของงานนำเสนอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์อินพุต. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | ตัวเลือกการโหลดเพิ่มเติม. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

คืนค่า หรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาในฟิลด์วันที่และเวลา. เวลาเริ่มต้นคือเวลาที่สร้างอ็อบเจ็กต์ Presentation นี้. อ่าน/เขียน java.util.Date.

**คืนค่า:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

คืนค่า หรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาในฟิลด์วันที่และเวลา. เวลาเริ่มต้นคือเวลาที่สร้างอ็อบเจ็กต์ Presentation นี้. อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่า Parent_Immediate object. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ปัจจุบัน. อ่านอย่างเดียว [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible ใช้เพื่อบ่งชี้ว่าตัวแทนส่วนท้ายสไลด์ไม่มีอยู่.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility ใช้เพื่อทำให้ตัวแทนส่วนท้ายสไลด์แสดงผล.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible ใช้เพื่อบ่งชี้ว่าตัวแทนหมายเลขสไลด์ไม่มีอยู่.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility ใช้เพื่อทำให้ตัวแทนหมายเลขหน้าแสดงผล.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible ใช้เพื่อบ่งชี้ว่าตัวแทนวันที่และเวลาในสไลด์ไม่มีอยู่.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility ใช้เพื่อทำให้ตัวแทนวันที่และเวลาในสไลด์แสดงผล.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText ใช้เพื่อกำหนดข้อความให้กับตัวแทนส่วนท้ายสไลด์.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText ใช้เพื่อกำหนดข้อความให้กับตัวแทนวันที่และเวลาในสไลด์.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility ใช้เพื่อทำให้สไลด์แม่และตัวแทนส่วนท้ายลูกทั้งหมดแสดงผล.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility ใช้เพื่อทำให้สไลด์แม่และตัวแทนหมายเลขหน้าลูกทั้งหมดแสดงผล.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility ใช้เพื่อทำให้สไลด์แม่และตัวแทนวันที่และเวลาลูกทั้งหมดแสดงผล.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText ใช้เพื่อกำหนดข้อความให้กับสไลด์แม่และตัวแทนส่วนท้ายลูกทั้งหมด.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText ใช้เพื่อกำหนดข้อความให้กับสไลด์แม่และตัวแทนวันที่และเวลาลูกทั้งหมด.
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

รับ manager ของสิทธิ์สำหรับงานนำเสนอ. อ่านอย่างเดียว [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**คืนค่า:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

คืนค่ารายการของสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation pres = new Presentation();
>  try
>  {
>      // ตั้งค่าสีพื้นหลังของ ISlide แรกเป็นสีน้ำเงิน
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
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // ตั้งค่าพื้นหลังด้วยรูปภาพ
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // ตั้งค่ารูปภาพ
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // เพิ่มรูปภาพไปยังคอลเลกชันภาพของงานนำเสนอ
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // เขียนงานนำเสนอลงดิสก์
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation เพื่อโหลดไฟล์งานนำเสนอต้นฉบับ
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // ใช้การเปลี่ยนสไลด์แบบวงกลมในสไลด์ที่ 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // ใช้การเปลี่ยนสไลด์แบบหวีในสไลด์ที่ 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // เขียนงานนำเสนอลงดิสก์
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // ใช้การเปลี่ยนสไลด์แบบวงกลมในสไลด์ที่ 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // ตั้งค่าเวลาเปลี่ยนสไลด์เป็น 3 วินาที
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // ใช้การเปลี่ยนสไลด์แบบหวีในสไลด์ที่ 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // ตั้งค่าเวลาเปลี่ยนสไลด์เป็น 5 วินาที
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // ใช้การเปลี่ยนสไลด์แบบซูมในสไลด์ที่ 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // ตั้งค่าเวลาเปลี่ยนสไลด์เป็น 7 วินาที
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // เขียนงานนำเสนอลงดิสก์
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

คืนค่ารายการของส่วนสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [ISectionCollection](../../com.aspose.slides/isectioncollection).

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

คืนค่าอ็อบเจ็กต์ขนาดสไลด์. อ่านอย่างเดียว [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // ตั้งค่าขนาดสไลด์ของงานนำเสนอที่สร้างขึ้นให้เท่ากับของต้นฉบับ
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // เมธอด SetSize ใช้สำหรับตั้งค่าขนาดสไลด์พร้อมสเกลเนื้อหาเพื่อให้พอดี
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // เมธอด SetSize ใช้สำหรับตั้งค่าขนาดสไลด์พร้อมขยายขนาดเนื้อหาให้ใหญ่ที่สุด
>          // บันทึกงานนำเสนอลงดิสก์
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // ขนาดกระดาษ A4
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

คืนค่าอ็อบเจ็กต์ขนาดสไลด์โน้ต. อ่านอย่างเดียว [INotesSize](../../com.aspose.slides/inotessize).

**คืนค่า:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

คืนค่ารายการของสไลด์เค้าโครงทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

คุณสามารถเข้าถึง API ทางเลือกสำหรับการเพิ่ม/แทรก/ลบ/โคลนสไลด์เค้าโครงโดยใช้คุณสมบัติ IMasterSlide.LayoutSlides.

**คืนค่า:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

คืนค่ารายการของสไลด์แม่ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation pres = new Presentation();
>  try
>  {
>      // ตั้งค่าสีพื้นหลังของ Master ISlide เป็นสีเขียวป่า
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // เขียนงานนำเสนอลงดิสก์
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // พยายามค้นหาโดยประเภทสไลด์เค้าโครง
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // สถานการณ์เมื่อ presentation ไม่มีเค้าโครงบางประเภท
>          // ไฟล์ presentation มีเพียงประเภทเค้าโครง Blank และ Custom
>          // แต่เค้าโครงประเภท Custom มีชื่อสไลด์ที่ต่างกัน,
>          // เช่น "Title", "Title and Content" เป็นต้น และสามารถใช้ชื่อนี้ในการเลือกเค้าโครงสไลด์ได้
>          // นอกจากนี้ยังสามารถใช้ชุดประเภท placeholder shape ได้ เช่น,
>          // สไลด์ Title ควรมีเฉพาะ placeholder ประเภท Title เท่านั้น
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
>      // เพิ่มสไลด์เปล่าพร้อมเค้าโครงสไลด์ที่เลือก
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // บันทึกงานนำเสนอ
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

คืนค่า notes master manager. อ่านอย่างเดียว [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**คืนค่า:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

คืนค่า handout master manager. อ่านอย่างเดียว [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**คืนค่า:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

คืนค่า fonts manager. อ่านอย่างเดียว [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // โหลดงานนำเสนอ
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // โหลดฟอนต์ต้นฉบับที่ต้องการแทนที่
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
>      // บันทึกงานนำเสนอ
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

คืนค่าสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

คืนค่าคอลเลกชันของผู้เขียนความคิดเห็น. อ่านอย่างเดียว [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**คืนค่า:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

คืนค่าอ็อบเจ็กต์ DocumentProperties ที่มีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร. อ่านอย่างเดียว [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**คืนค่า:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

คืนค่าคอลเลกชันของภาพทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // สร้างงานนำเสนอใหม่ที่ภาพจะถูกเพิ่มเข้าไป
>  Presentation pres = new Presentation();
>  try
>  {
>      // สมมติว่าเรามีไฟล์รูปภาพขนาดใหญ่ที่ต้องการใส่ลงในงานนำเสนอ
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // มาลองเพิ่มภาพลงในงานนำเสนอ - เราเลือกพฤติกรรม KeepLocked เพราะเราต้องการ
>          // ไม่ได้ตั้งใจเข้าถึงไฟล์ "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // บันทึกงานนำเสนอ ระหว่างที่สร้างงานนำเสนอขนาดใหญ่ การใช้หน่วยความจำ
>          // ยังคงต่ำตลอดระยะอายุของอ็อบเจ็กต์ pres
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
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // เพิ่มภาพลงในงานนำเสนอ
>          IPPImage image = pres.getImages().addImage(fos);
>          // สร้าง picture frame บนสไลด์ 1 โดยอิงจากภาพที่เพิ่มไว้ก่อนหน้า
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
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

คืนค่าคอลเลกชันของไฟล์เสียงฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
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

คืนค่าคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [IVideoCollection](../../com.aspose.slides/ivideocollection).

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

คืนค่าการตั้งค่าแสดงสไลด์โชว์ของงานนำเสนอ.

**คืนค่า:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

คืนค่าคอลเลกชันของลายเซ็นที่ใช้เซ็นงานนำเสนอ. อ่านอย่างเดียว [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

คืนค่าข้อมูลกำหนดเองของงานนำเสนอ. อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**คืนค่า:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

คืนค่าทุกส่วนข้อมูลกำหนดเองในงานนำเสนอ. อ่านอย่างเดียว ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // วนลูปทั้งหมดส่วน XML ที่กำหนดเอง
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

รับหรือกำหนดโครงการ VBA ที่มีมาโครของงานนำเสนอ. อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject).

**คืนค่า:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

รับหรือกำหนดโครงการ VBA ที่มีมาโครของงานนำเสนอ. อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงอย่างง่ายต่อไฮเปอร์ลิงก์ทั้งหมดที่อยู่ในสไลด์ของงานนำเสนอ (ไม่รวมสไลด์แม่, เค้าโครง, โน้ต). อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**คืนค่า:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

รับคุณสมบัติการมองเห็นทั่วงานนำเสนอ. อ่านอย่างเดียว [IViewProperties](../../com.aspose.slides/iviewproperties).

**คืนค่า:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

เป็นตัวแทนของหมายเลขสไลด์แรกในงานนำเสนอ

**คืนค่า:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

เป็นตัวแทนของหมายเลขสไลด์แรกในงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

คืนค่าคอลเลกชันของป้ายความอ่อนไหวที่ใช้กับเอกสารงานนำเสนอ. อ่านอย่างเดียว [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // พิมพ์ป้ายที่ถูกนำไปใช้
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // เพิ่มป้ายใหม่
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // รับ Id ของป้ายความอ่อนไหวจากนโยบาย
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // รับตัวระบุไซต์ Azure AD จากนโยบาย
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

คืนข้อมุลเกี่ยวกับรูปแบบที่งานนำมาโหลด. อ่านอย่างเดียว [SourceFormat](../../com.aspose.slides/sourceformat).

**คืนค่า:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

คืนค่า master theme. อ่านอย่างเดียว [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
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

บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังไฟล์ในรูปแบบที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังไฟล์ในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม.

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

บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม.

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

บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่เป็น XAML markup.

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

คืนค่าอ็อบเจ็กต์ Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ.

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

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| slides | int[] | อาเรย์ตำแหน่งสไลด์ เริ่มจาก 1. |

**คืนค่า:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยการสเกลแบบกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| scaleX | float | ค่าที่ใช้สเกล Thumbnail ในแนวแกน X. |
| scaleY | float | ค่าที่ใช้สเกล Thumbnail ในแนวแกน Y. |

**คืนค่า:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยการสเกลแบบกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| slides | int[] | อาเรย์ตำแหน่งสไลด์ เริ่มจาก 1. |
| scaleX | float | ค่าที่ใช้สเกล Thumbnail ในแนวแกน X. |
| scaleY | float | ค่าที่ใช้สเกล Thumbnail ในแนวแกน Y. |

**คืนค่า:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยขนาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| imageSize | [Size](../../com.aspose.slides.android/size) | ขนาดของภาพที่ต้องการสร้าง. |

**คืนค่า:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยขนาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือก Tiff. |
| slides | int[] | อาเรย์ตำแหน่งสไลด์ เริ่มจาก 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | ขนาดของภาพที่ต้องการสร้าง. |

**คืนค่า:**
com.aspose.slides.IImage[] - Image objects.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของงานนำเสนอไปยังไฟล์ในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง. |
| slides | int[] | อาเรย์ตำแหน่งสไลด์ เริ่มจาก 1. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของงานนำเสนอไปยังไฟล์ในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง. |
| slides | int[] | อาเรย์ตำแหน่งสไลด์ เริ่มจาก 1. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต. |
| slides | int[] | อาเรย์ตำแหน่งสไลด์ เริ่มจาก 1. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
| slides | int[] | อาเรย์ตำแหน่งสไลด์ เริ่มจาก 1. |
| format | int | รูปแบบของข้อมูลที่ส่งออก. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่รองรับทั้งหมดในทุกสไลด์.

### dispose() {#dispose--}
```
public final void dispose()
```

ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจ็กต์ Presentation นี้.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่า presentation พาเรนท์ของข้อความ. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // เน้นข้อความ 'the' ทั้งหมดที่แยกจากกัน
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการไฮไลท์. |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // เน้นข้อความ 'the' ทั้งหมดที่แยกจากกัน
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ต้องการไฮไลท์. |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | วัตถุ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

ไฮไลท์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ.

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // ไฮไลท์คำนั้นทั้งหมดที่มีความยาว 10 ตัวอักษรหรือมากกว่า
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ทั่วไป java.util.regex.Pattern เพื่อดึงสตริงที่ต้องการไฮไลท์. |
| highlightColor | java.lang.Integer | สีที่ใช้ไฮไลท์ข้อความ. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | วัตถุ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

แทนที่การเกิดขึ้นทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ.

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การเกิดขึ้นทั้งหมดของ 'the' ที่แยกจากกันด้วย '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| oldText | java.lang.String | สตริงที่ต้องการแทนที่. |
| newText | java.lang.String | สตริงที่ใช้แทนที่การเกิดขึ้นทั้งหมดของ oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | วัตถุ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

แทนที่การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสตริงที่ระบุ.

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // แทนที่คำทั้งหมดที่มีความยาว 10 สัญลักษณ์หรือมากกว่าเป็น '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ทั่วไป java.util.regex.Pattern เพื่อดึงสตริงที่ต้องการแทน. |
| newText | java.lang.String | สตริงที่ใช้แทนการจับคู่ทั้งหมดของสตริงที่ต้องการแทน. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | วัตถุ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |