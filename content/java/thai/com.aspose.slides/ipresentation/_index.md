---
title: IPresentation
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เอกสารนำเสนอ
type: docs
url: /th/com.aspose.slides/ipresentation/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

เอกสารการนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | คืนค่าหรือกำหนดวันที่และเวลาซึ่งจะแทนที่เนื้อหาของฟิลด์ datetime |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | คืนค่าหรือกำหนดวันที่และเวลาซึ่งจะแทนที่เนื้อหาของฟิลด์ datetime |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของการนำเสนอ |
| [getProtectionManager()](#getProtectionManager--) | รับผู้จัดการสิทธิ์สำหรับการนำเสนอนี้ |
| [getSlides()](#getSlides--) | คืนค่ารายการสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ |
| [getSections()](#getSections--) | คืนค่ารายการส่วนของสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ |
| [getSlideSize()](#getSlideSize--) | คืนค่าอ็อบเจกต์ขนาดสไลด์ |
| [getNotesSize()](#getNotesSize--) | คืนค่าอ็อบเจกต์ขนาดสไลด์บันทึกย่อ |
| [getLayoutSlides()](#getLayoutSlides--) | คืนค่ารายการสไลด์เค้าโครงทั้งหมดที่กำหนดไว้ในการนำเสนอ |
| [getMasters()](#getMasters--) | คืนค่ารายการสไลด์แม่ทั้งหมดที่กำหนดไว้ในการนำเสนอ |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | คืนค่า notes master manager |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | คืนค่า handout master manager |
| [getFontsManager()](#getFontsManager--) | คืนค่า fonts manager |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | คืนค่า default text style สำหรับรูปร่าง |
| [getCommentAuthors()](#getCommentAuthors--) | คืนค่าคอลเลกชันของผู้เขียนความคิดเห็น |
| [getDocumentProperties()](#getDocumentProperties--) | คืนค่า DocumentProperties object ซึ่งบรรจุคุณสมบัติมาตรฐานและคุณสมบัติกำหนดเองของเอกสาร |
| [getImages()](#getImages--) | คืนค่าคอลเลกชันของรูปภาพทั้งหมดในการนำเสนอ |
| [getAudios()](#getAudios--) | คืนค่าคอลเลกชันของไฟล์เสียงที่ฝังอยู่ทั้งหมดในการนำเสนอ |
| [getVideos()](#getVideos--) | คืนค่าคอลเลกชันของไฟล์วิดีโอที่ฝังอยู่ทั้งหมดในการนำเสนอ |
| [getCustomData()](#getCustomData--) | คืนค่าข้อมูลกำหนดเองของการนำเสนอ |
| [getVbaProject()](#getVbaProject--) | รับ VBA project กับแมโครของการนำเสนอ |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | รับ VBA project กับแมโครของการนำเสนอ |
| [getSourceFormat()](#getSourceFormat--) | คืนค่าข้อมูลเกี่ยวกับรูปแบบที่การนำเสนอถูกโหลดมา |
| [getMasterTheme()](#getMasterTheme--) | คืนค่า master theme ของการนำเสนอ |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์การนำเสนอ (ไม่รวมสไลด์แม่, เค้าโครง, หรือสไลด์บันทึกย่อ) |
| [getViewProperties()](#getViewProperties--) | รับคุณสมบัติมุมมองทั่วทั้งการนำเสนอ |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | คืนค่าทุกส่วนข้อมูลกำหนดเองในการนำเสนอ |
| [getDigitalSignatures()](#getDigitalSignatures--) | คืนค่าคอลเลกชันของลายเซ็นที่ใช้ลงนามการนำเสนอ |
| [getSensitivityLabels()](#getSensitivityLabels--) | คืนค่าคอลเลกชันของป้ายความอ่อนไหวที่ใช้กับเอกสารการนำเสนอ |
| [save(String fname, int format)](#save-java.lang.String-int-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นสตรีมด้วยรูปแบบที่ระบุ |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นสตรีมด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นสตรีมด้วยรูปแบบที่ระบุ |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นสตรีมด้วยรูปแบบที่ระบุ |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่เป็น XAML markup |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอ |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | คืนค่าอ็อบเจกต์ Thumbnail IImage สำหรับสไลด์ที่ระบุของการนำเสนอ |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอโดยปรับสเกลตามที่กำหนด |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอโดยปรับสเกลตามที่กำหนด |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยขนาดที่ระบุ |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยขนาดที่ระบุ |
| [getSlideById(long id)](#getSlideById-long-) | คืนค่า Slide, MasterSlide หรือ LayoutSlide ตาม Id |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | เชื่อมต่อรันที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับได้ในสไลด์ทั้งหมด |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | เน้นข้อความตัวอย่างทั้งหมดด้วยสีที่ระบุ |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | เน้นข้อความตัวอย่างทั้งหมดด้วยสีที่ระบุ |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | เน้นผลแมตช์ของ regular expression ด้วยสีที่ระบุ |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่ข้อความที่ระบุทั้งหมดด้วยข้อความอื่นที่ระบุ |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่ผลแมตช์ของ regular expression ด้วยสตริงที่ระบุ |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

คืนค่าหรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาของฟิลด์ datetime การสร้างอ็อบเจกต์ Presentation นี้โดยค่าเริ่มต้น อ่าน/เขียน java.util.Date

**คืนค่า:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

คืนค่าหรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาของฟิลด์ datetime การสร้างอ็อบเจกต์ Presentation นี้โดยค่าเริ่มต้น อ่าน/เขียน java.util.Date

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของการนำเสนอ อ่านอย่างเดียว [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

**คืนค่า:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

รับผู้จัดการสิทธิ์สำหรับการนำเสนอนี้ อ่านอย่างเดียว [IProtectionManager](../../com.aspose.slides/iprotectionmanager)

**คืนค่า:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

คืนค่ารายการสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ อ่านอย่างเดียว [ISlideCollection](../../com.aspose.slides/islidecollection)

**คืนค่า:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

คืนค่ารายการส่วนของสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ อ่านอย่างเดียว [ISectionCollection](../../com.aspose.slides/isectioncollection)

**คืนค่า:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

คืนค่าอ็อบเจกต์ขนาดสไลด์ อ่านอย่างเดียว [ISlideSize](../../com.aspose.slides/islidesize)

**คืนค่า:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

คืนค่าอ็อบเจกต์ขนาดสไลด์บันทึกย่อ อ่านอย่างเดียว [INotesSize](../../com.aspose.slides/inotessize)

**คืนค่า:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

คืนค่ารายการสไลด์เค้าโครงทั้งหมดที่กำหนดไว้ในการนำเสนอ อ่านอย่างเดียว [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

--------------------

คุณสามารถเข้าถึง API ทางเลือกสำหรับการเพิ่ม/แทรก/ลบ/คัดลอกสไลด์เค้าโครงโดยใช้คุณสมบัติ IMasterSlide.LayoutSlides

**คืนค่า:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

คืนค่ารายการสไลด์แม่ทั้งหมดที่กำหนดไว้ในการนำเสนอ อ่านอย่างเดียว [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

**คืนค่า:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

คืนค่า notes master manager อ่านอย่างเดียว [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

**คืนค่า:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

คืนค่า handout master manager อ่านอย่างเดียว [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

**คืนค่า:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

คืนค่า fonts manager อ่านอย่างเดียว [IFontsManager](../../com.aspose.slides/ifontsmanager)

**คืนค่า:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

คืนค่า default text style สำหรับรูปร่าง อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle)

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

คืนค่าคอลเลกชันของผู้เขียนความคิดเห็น อ่านอย่างเดียว [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

**คืนค่า:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

คืนค่า DocumentProperties object ซึ่งบรรจุคุณสมบัติมาตรฐานและคุณสมบัติกำหนดเองของเอกสาร อ่านอย่างเดียว [IDocumentProperties](../../com.aspose.slides/idocumentproperties)

**คืนค่า:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

คืนค่าคอลเลกชันของรูปภาพทั้งหมดในการนำเสนอ อ่านอย่างเดียว [IImageCollection](../../com.aspose.slides/iimagecollection)

**คืนค่า:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

คืนค่าคอลเลกชันของไฟล์เสียงที่ฝังอยู่ทั้งหมดในการนำเสนอ อ่านอย่างเดียว [IAudioCollection](../../com.aspose.slides/iaudiocollection)

**คืนค่า:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

คืนค่าคอลเลกชันของไฟล์วิดีโอที่ฝังอยู่ทั้งหมดในการนำเสนอ อ่านอย่างเดียว [IVideoCollection](../../com.aspose.slides/ivideocollection)

**คืนค่า:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

คืนค่าข้อมูลกำหนดเองของการนำเสนอ อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata)

**คืนค่า:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

รับ VBA project กับแมโครของการนำเสนอ อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject)

**คืนค่า:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

รับ VBA project กับแมโครของการนำเสนอ อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

คืนค่าข้อมูลเกี่ยวกับรูปแบบที่การนำเสนอถูกโหลดมา อ่านอย่างเดียว [SourceFormat](../../com.aspose.slides/sourceformat)

**คืนค่า:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

คืนค่า master theme ของการนำเสนอ อ่านอย่างเดียว [IMasterTheme](../../com.aspose.slides/imastertheme)

**คืนค่า:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์การนำเสนอ (ไม่รวมสไลด์แม่, เค้าโครง, หรือสไลด์บันทึกย่อ) อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

**คืนค่า:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

รับคุณสมบัติมุมมองทั่วทั้งการนำเสนอ อ่านอย่างเดียว [IViewProperties](../../com.aspose.slides/iviewproperties)

**คืนค่า:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

แสดงหมายเลขสไลด์แรกในการนำเสนอ อ่าน/เขียน int

**คืนค่า:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

แสดงหมายเลขสไลด์แรกในการนำเสนอ อ่าน/เขียน int

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

คืนค่าทุกส่วนข้อมูลกำหนดเองในการนำเสนอ อ่านอย่างเดียว ICustomXmlPart[]

**คืนค่า:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

คืนค่าคอลเลกชันของลายเซ็นที่ใช้ลงนามการนำเสนอ อ่านอย่างเดียว [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

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

**คืนค่า:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

คืนค่าคอลเลกชันของป้ายความอ่อนไหวที่ใช้กับเอกสารการนำเสนอ อ่านอย่างเดียว [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // พิมพ์ป้ายกำกับที่ใช้
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // เพิ่มป้ายกำกับใหม่
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // ดึง Id ของป้ายกำกับความอ่อนไหมาจากนโยบาย
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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | พาธไปยังไฟล์ที่สร้าง |
| format | int | รูปแบบของข้อมูลที่ส่งออก |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นสตรีมด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมผลลัพธ์ |
| format | int | รูปแบบของข้อมูลที่ส่งออก |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | พาธไปยังไฟล์ที่สร้าง |
| format | int | รูปแบบของข้อมูลที่ส่งออก |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต |
| format | int | รูปแบบของข้อมูลที่ส่งออก |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| format | int | รูปแบบของข้อมูลที่ส่งออก |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| format | int | รูปแบบของข้อมูลที่ส่งออก |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| format | int | รูปแบบของข้อมูลที่ส่งออก |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเอาต์พุต |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| format | int | รูปแบบของข้อมูลที่ส่งออก |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังชุดไฟล์ที่เป็นการทำเครื่องหมาย XAML

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | ตัวเลือกรูปแบบ XAML |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

ส่งคืนอ็อบเจ็กต์ภาพย่อสำหรับสไลด์ทั้งหมดของการนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |

**ส่งคืน:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

ส่งคืนอ็อบเจ็กต์ IImage ย่อสำหรับสไลด์ที่ระบุของการนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |

**ส่งคืน:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

ส่งคืนอ็อบเจ็กต์ภาพย่อสำหรับสไลด์ทั้งหมดของการนำเสนอด้วยการปรับสเกลแบบกำหนดเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| scaleX | float | ค่าที่ใช้ปรับสเกลภาพย่อนี้ในแนวแกน x |
| scaleY | float | ค่าที่ใช้ปรับสเกลภาพย่อนี้ในแนวแกน y |

**ส่งคืน:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

ส่งคืนอ็อบเจ็กต์ภาพย่อสำหรับสไลด์ที่ระบุของการนำเสนอด้วยการปรับสเกลแบบกำหนดเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| scaleX | float | ค่าที่ใช้ปรับสเกลภาพย่อนี้ในแนวแกน x |
| scaleY | float | ค่าที่ใช้ปรับสเกลภาพย่อนี้ในแนวแกน y |

**ส่งคืน:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

ส่งคืนอ็อบเจ็กต์ภาพย่อสำหรับสไลด์ทั้งหมดของการนำเสนอด้วยขนาดที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| imageSize | java.awt.Dimension | ขนาดของภาพที่จะสร้าง |

**ส่งคืน:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

ส่งคืนอ็อบเจ็กต์ภาพย่อสำหรับสไลด์ที่ระบุของการนำเสนอด้วยขนาดที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| slides | int[] | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| imageSize | java.awt.Dimension | ขนาดของภาพที่จะสร้าง |

**ส่งคืน:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

ส่งคืน Slide, MasterSlide หรือ LayoutSlide ตาม Id

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| id | long | Id ของสไลด์ |

**ส่งคืน:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

รวม run ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปทรงที่ยอมรับได้ทั้งหมดในทุกสไลด์

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

ไฮไลท์ทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // ไฮไลท์คำ 'the' ทั้งหมดที่แยกจากกัน
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะไฮไลท์ |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลท์ข้อความ |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

ไฮไลท์ทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // ไฮไลท์คำ 'the' ทั้งหมดที่แยกจากกัน
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะไฮไลท์ |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลท์ข้อความ |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

ไฮไลท์ทั้งหมดที่ตรงกับนิพจน์ปกติกับสีที่ระบุ

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // ไฮไลท์คำ 'the' ทั้งหมดที่แยกจากกัน
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ปกติ java.util.regex.Pattern เพื่อดึงสตริงที่จะไฮไลท์ |
| highlightColor | java.awt.Color | สีที่ใช้ไฮไลท์ข้อความ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

แทนที่ทั้งหมดของข้อความที่ระบุด้วยข้อความใหม่ที่ระบุ

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การเกิดคำ 'the' ที่แยกจากกันทั้งหมดด้วย '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| oldText | java.lang.String | สตริงที่จะถูกแทนที่ |
| newText | java.lang.String | สตริงที่จะแทนที่ทุกการปรากฏของ oldText |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

แทนที่ทั้งหมดที่ตรงกับนิพจน์ปกติกับสตริงที่ระบุ

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่คำ 'the' ที่แยกจากกันทั้งหมดด้วย '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| regex | java.util.regex.Pattern | นิพจน์ปกติ java.util.regex.Pattern เพื่อดึงสตริงที่จะแทนที่ |
| newText | java.lang.String | สตริงที่จะแทนที่ทุกการปรากฏของสตริงที่ต้องการแทนที่ |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) |