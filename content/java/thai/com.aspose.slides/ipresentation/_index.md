---
title: IPresentation
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: เอกสารการนำเสนอ
type: docs
url: /th/com.aspose.slides/ipresentation/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

เอกสารการนำเสนอ
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | ส่งคืนหรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาของฟิลด์ datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | ส่งคืนหรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาของฟิลด์ datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ส่งคืนตัวจัดการ HeaderFooter ของการนำเสนอ. |
| [getProtectionManager()](#getProtectionManager--) | ดึงตัวจัดการสิทธิ์ของการนำเสนอนี้. |
| [getSlides()](#getSlides--) | ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ. |
| [getSections()](#getSections--) | ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ. |
| [getSlideSize()](#getSlideSize--) | ส่งคืนอ็อบเจกต์ขนาดสไลด์. |
| [getNotesSize()](#getNotesSize--) | ส่งคืนอ็อบเจกต์ขนาดสไลด์โน้ต. |
| [getLayoutSlides()](#getLayoutSlides--) | ส่งคืนรายการของสไลด์เลย์เอาต์ทั้งหมดที่กำหนดไว้ในการนำเสนอ. |
| [getMasters()](#getMasters--) | ส่งคืนรายการของมาสเตอร์สไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | ส่งคืนตัวจัดการโน้ตมาสเตอร์. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | ส่งคืนตัวจัดการแฮนด์เอาต์มาสเตอร์. |
| [getFontsManager()](#getFontsManager--) | ส่งคืนตัวจัดการฟอนต์. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | ส่งคืนสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง. |
| [getCommentAuthors()](#getCommentAuthors--) | ส่งคืนคอลเลกชันของผู้เขียนคอมเมนต์. |
| [getDocumentProperties()](#getDocumentProperties--) | ส่งคืนอ็อบเจกต์ DocumentProperties ที่มีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร. |
| [getImages()](#getImages--) | ส่งคืนคอลเลกชันของภาพทั้งหมดในการนำเสนอ. |
| [getAudios()](#getAudios--) | ส่งคืนคอลเลกชันของไฟล์เสียงฝังทั้งหมดในการนำเสนอ. |
| [getVideos()](#getVideos--) | ส่งคืนคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในการนำเสนอ. |
| [getCustomData()](#getCustomData--) | ส่งคืนข้อมูลกำหนดเองของการนำเสนอ. |
| [getVbaProject()](#getVbaProject--) | ดึงโปรเจกต์ VBA พร้อมแมคโครของการนำเสนอ. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | ดึงโปรเจกต์ VBA พร้อมแมคโครของการนำเสนอ. |
| [getSourceFormat()](#getSourceFormat--) | ส่งคืนข้อมูลเกี่ยวกับรูปแบบที่การนำเสนอถูกโหลด. |
| [getMasterTheme()](#getMasterTheme--) | ส่งคืนธีมมาสเตอร์ของการนำเสนอ. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงง่ายแก่ทุกไฮเปอร์ลิงก์ที่อยู่ในสไลด์การนำเสนอทั้งหมด (ไม่รวมมาสเตอร์, เลย์เอาต์, สไลด์โน้ต). |
| [getViewProperties()](#getViewProperties--) | ดึงคุณสมบัติการมองเห็นทั่วการนำเสนอ. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | แสดงหมายเลขสไลด์แรกในการนำเสนอ. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | แสดงหมายเลขสไลด์แรกในการนำเสนอ. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | ส่งคืนส่วนข้อมูลกำหนดเองทั้งหมดในการนำเสนอ. |
| [getDigitalSignatures()](#getDigitalSignatures--) | ส่งคืนคอลเลกชันของลายเซ็นที่ใช้ในการลงนามการนำเสนอ. |
| [getSensitivityLabels()](#getSensitivityLabels--) | ส่งคืนคอลเลกชันของป้ายความอ่อนไหวที่ใช้กับเอกสารการนำเสนอ. |
| [save(String fname, int format)](#save-java.lang.String-int-) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่กำหนด. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมด้วยรูปแบบที่กำหนด. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่กำหนดและตัวเลือกเพิ่มเติม. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมด้วยรูปแบบที่กำหนดและตัวเลือกเพิ่มเติม. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่แสดง XAML markup. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอ. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | ส่งคืนอ็อบเจกต์ Thumbnail IImage สำหรับสไลด์ที่ระบุของการนำเสนอ. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยการสเกลที่กำหนดเอง. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยการสเกลที่กำหนดเอง. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยขนาดที่ระบุ. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยขนาดที่ระบุ. |
| [getSlideById(long id)](#getSlideById-long-) | ส่งคืน Slide, MasterSlide หรือ LayoutSlide ตาม Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่ยอมรับทั้งหมดในทุกสไลด์. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | ทำให้ตรงกับข้อความตัวอย่างทั้งหมดเป็นสีที่ระบุ. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | ทำให้ตรงกับข้อความตัวอย่างทั้งหมดเป็นสีที่ระบุ. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | ทำให้ตรงกับนิพจน์ปกติทั้งหมดเป็นสีที่ระบุ. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการเกิดของข้อความที่ระบุด้วยข้อความที่ระบุอื่น. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการตรงกับนิพจน์ปกติด้วยสตริงที่ระบุ. |
| [refreshChartsData()](#refreshChartsData--) | โหลดข้อมูลของแผนภูมิทั้งหมดในการนำเสนอจากเวิร์กบุ๊คต้นฉบับ. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | โหลดข้อมูลของแผนภูมิทั้งหมดในการนำเสนอจากเวิร์กบุ๊คต้นฉบับ. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

ส่งคืนหรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาของฟิลด์ datetime. เวลาโดยปริยายของการสร้างอ็อบเจกต์ Presentation นี้. อ่าน/เขียน java.util.Date.

**ส่งคืน:**  
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

ส่งคืนหรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาของฟิลด์ datetime. เวลาโดยปริยายของการสร้างอ็อบเจกต์ Presentation นี้. อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

ส่งคืนตัวจัดการ HeaderFooter ของการนำเสนอ. อ่านอย่างเดียว [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**ส่งคืน:**  
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

ดึงตัวจัดการสิทธิ์ของการนำเสนอนี้. อ่านอย่างเดียว [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**ส่งคืน:**  
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ. อ่านอย่างเดียว [ISlideCollection](../../com.aspose.slides/islidecollection).

**ส่งคืน:**  
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ. อ่านอย่างเดียว [ISectionCollection](../../com.aspose.slides/isectioncollection).

**ส่งคืน:**  
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

ส่งคืนอ็อบเจกต์ขนาดสไลด์. อ่านอย่างเดียว [ISlideSize](../../com.aspose.slides/islidesize).

**ส่งคืน:**  
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

ส่งคืนอ็อบเจกต์ขนาดสไลด์โน้ต. อ่านอย่างเดียว [INotesSize](../../com.aspose.slides/inotessize).

**ส่งคืน:**  
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

ส่งคืนรายการของสไลด์เลย์เอาต์ทั้งหมดที่กำหนดไว้ในการนำเสนอ. อ่านอย่างเดียว [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

You can access to alternative API for adding/inserting/removing/cloning layout slides by using IMasterSlide.LayoutSlides property.

**ส่งคืน:**  
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

ส่งคืนรายการของมาสเตอร์สไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ. อ่านอย่างเดียว [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**ส่งคืน:**  
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

ส่งคืนตัวจัดการโน้ตมาสเตอร์. อ่านอย่างเดียว [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**ส่งคืน:**  
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

ส่งคืนตัวจัดการแฮนด์เอาต์มาสเตอร์. อ่านอย่างเดียว [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**ส่งคืน:**  
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

ส่งคืนตัวจัดการฟอนต์. อ่านอย่างเดียว [IFontsManager](../../com.aspose.slides/ifontsmanager).

**ส่งคืน:**  
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

ส่งคืนสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**ส่งคืน:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

ส่งคืนคอลเลกชันของผู้เขียนคอมเมนต์. อ่านอย่างเดียว [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**ส่งคืน:**  
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

ส่งคืนอ็อบเจกต์ DocumentProperties ที่มีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร. อ่านอย่างเดียว [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**ส่งคืน:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

ส่งคืนคอลเลกชันของภาพทั้งหมดในการนำเสนอ. อ่านอย่างเดียว [IImageCollection](../../com.aspose.slides/iimagecollection).

**ส่งคืน:**  
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

ส่งคืนคอลเลกชันของไฟล์เสียงฝังทั้งหมดในการนำเสนอ. อ่านอย่างเดียว [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**ส่งคืน:**  
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

ส่งคืนคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในการนำเสนอ. อ่านอย่างเดียว [IVideoCollection](../../com.aspose.slides/ivideocollection).

**ส่งคืน:**  
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

ส่งคืนข้อมูลกำหนดเองของการนำเสนอ. อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**ส่งคืน:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

ดึงโปรเจกต์ VBA พร้อมแมคโครของการนำเสนอ. อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject).

**ส่งคืน:**  
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

ดึงโปรเจกต์ VBA พร้อมแมคโครของการนำเสนอ. อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

ส่งคืนข้อมูลเกี่ยวกับรูปแบบที่การนำเสนอถูกโหลด. อ่านอย่างเดียว [SourceFormat](../../com.aspose.slides/sourceformat).

**ส่งคืน:**  
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

ส่งคืนธีมมาสเตอร์ของการนำเสนอ. อ่านอย่างเดียว [IMasterTheme](../../com.aspose.slides/imastertheme).

**ส่งคืน:**  
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงง่ายแก่ทุกไฮเปอร์ลิงก์ที่อยู่ในสไลด์การนำเสนอทั้งหมด (ไม่รวมมาสเตอร์, เลย์เอาต์, สไลด์โน้ต). อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**ส่งคืน:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

ดึงคุณสมบัติการมองเห็นทั่วการนำเสนอ. อ่านอย่างเดียว [IViewProperties](../../com.aspose.slides/iviewproperties).

**ส่งคืน:**  
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

แสดงหมายเลขสไลด์แรกในการนำเสนอ. อ่าน/เขียน int.

**ส่งคืน:**  
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

แสดงหมายเลขสไลด์แรกในการนำเสนอ. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

ส่งคืนส่วนข้อมูลกำหนดเองทั้งหมดในการนำเสนอ. อ่านอย่างเดียว ICustomXmlPart[].

**ส่งคืน:**  
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

ส่งคืนคอลเลกชันของลายเซ็นที่ใช้ในการลงนามการนำเสนอ. อ่านอย่างเดียว [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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


**ส่งคืน:**  
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

ส่งคืนคอลเลกชันของป้ายความอ่อนไหวที่ใช้กับเอกสารการนำเสนอ. อ่านอย่างเดียว [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // พิมพ์ป้ายกำกับที่ถูกใช้งาน
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // เพิ่มป้ายกำกับใหม่
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // ดึง Id ของป้ายกำกับความรู้สึกจากนโยบาย
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // ดึงตัวระบุไซต์ Azure AD จากนโยบาย
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**  
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมด้วยรูปแบบที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
บันทึกสไลด์ทั้งหมดของงานพรีเซนเทชันลงในไฟล์ด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง |
| format | int | รูปแบบของข้อมูลที่ส่งออก |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

บันทึกสไลด์ทั้งหมดของงานพรีเซนเทชันลงในสตรีมด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต |
| format | int | รูปแบบของข้อมูลที่ส่งออก |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของงานพรีเซนเทชันลงในไฟล์ด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | int[] | อาร์เรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | int | รูปแบบของข้อมูลที่ส่งออก |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของงานพรีเซนเทชันลงในไฟล์ด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | int[] | อาร์เรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | int | รูปแบบของข้อมูลที่ส่งออก |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของงานพรีเซนเทชันลงในสตรีมด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต |
| slides | int[] | อาร์เรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | int | รูปแบบของข้อมูลที่ส่งออก |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของงานพรีเซนเทชันลงในสตรีมด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต |
| slides | int[] | อาร์เรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | int | รูปแบบของข้อมูลที่ส่งออก |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

บันทึกสไลด์ทั้งหมดของงานพรีเซนเทชันเป็นชุดไฟล์ที่เป็นมาร์กอัป XAML

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
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | ตัวเลือกรูปแบบ XAML |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานพรีเซนเทชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

คืนค่าอ็อบเจ็กต์ Thumbnail IImage สำหรับสไลด์ที่ระบุของงานพรีเซนเทชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| slides | int[] | อาร์เรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานพรีเซนเทชันโดยกำหนดอัตราสเกลเอง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| scaleX | float | ค่าที่ใช้ปรับสเกล Thumbnail นี้ในทิศทางแกน X |
| scaleY | float | ค่าที่ใช้ปรับสเกล Thumbnail นี้ในทิศทางแกน Y |

**Returns:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานพรีเซนเทชันโดยกำหนดอัตราสเกลเอง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| slides | int[] | อาร์เรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| scaleX | float | ค่าที่ใช้ปรับสเกล Thumbnail นี้ในทิศทางแกน X |
| scaleY | float | ค่าที่ใช้ปรับสเกล Thumbnail นี้ในทิศทางแกน Y |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานพรีเซนเทชันโดยกำหนดขนาดที่ต้องการ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| imageSize | java.awt.Dimension | ขนาดของภาพที่ต้องการสร้าง |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานพรีเซนเทชันโดยกำหนดขนาดที่ต้องการ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| slides | int[] | อาร์เรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| imageSize | java.awt.Dimension | ขนาดของภาพที่ต้องการสร้าง |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

คืนค่า Slide, MasterSlide หรือ LayoutSlide ตาม Id

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id ของสไลด์ |

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

รวม run ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่รับได้ในทุกสไลด์

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

ไฮไลท์ข้อความทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // ไฮไลต์ทุกการปรากฏของคำ 'the' ที่แยกออกจากกัน
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะไฮไลท์ |
| highlightColor | java.awt.Color | สีที่จะใช้ไฮไลท์ข้อความ |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

ไฮไลท์ข้อความทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // ไฮไลต์ทุกการปรากฏของคำ 'the' ที่แยกออกจากกัน
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะไฮไลท์ |
| highlightColor | java.awt.Color | สีที่จะใช้ไฮไลท์ข้อความ |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

ไฮไลท์การจับคู่ทั้งหมดของ regular expression ด้วยสีที่ระบุ

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // ไฮไลต์ทุกการปรากฏของคำ 'the' ที่แยกออกจากกัน
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | regular expression java.util.regex.Pattern เพื่อหาสตริงที่จะไฮไลท์ |
| highlightColor | java.awt.Color | สีที่จะใช้ไฮไลท์ข้อความ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การปรากฏของคำ 'the' ที่แยกออกจากกันทั้งหมดด้วย '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | สตริงที่จะถูกแทนที่ |
| newText | java.lang.String | สตริงที่จะแทนที่การปรากฏทั้งหมดของ oldText |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

แทนที่การจับคู่ทั้งหมดของ regular expression ด้วยสตริงที่ระบุ

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การปรากฏของคำ 'the' ที่แยกออกจากกันทั้งหมดด้วย '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | regular expression java.util.regex.Pattern เพื่อหาสตริงที่จะแทนที่ |
| newText | java.lang.String | สตริงที่จะแทนที่การปรากฏทั้งหมดของสตริงที่ต้องการแทนที่ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

โหลดข้อมูลสำหรับแผนภูมิทั้งหมดในงานพรีเซนเทชันจากเวิร์กบุ๊กต้นทาง

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public abstract void refreshChartsData(boolean skipFailedCharts)
```

โหลดข้อมูลสำหรับแผนภูมิทั้งหมดในงานพรีเซนเทชันจากเวิร์กบุ๊กต้นทาง

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| skipFailedCharts | boolean | กำหนดว่ากระบวนการรีเฟรชจะดำเนินต่อหากแผนภูมิหนึ่งล้มเหลวในการอัปเดตหรือไม่ หาก true จะข้ามแผนภูมิที่ทำให้เกิดข้อยกเว้น; หาก false จะปล่อยให้ข้อยกเว้นถูกส่งต่อ |
