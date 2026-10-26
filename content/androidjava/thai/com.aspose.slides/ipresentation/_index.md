---
title: IPresentation
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เอกสารการนำเสนอ
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
| [getCurrentDateTime()](#getCurrentDateTime--) | คืนค่าหรือกำหนดวันและเวลาที่จะใช้แทนเนื้อหาของฟิลด์วันเวลา |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | คืนค่า或กำหนดวันและเวลาที่จะใช้แทนเนื้อหาของฟิลด์วันเวลา |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของการนำเสนอ |
| [getProtectionManager()](#getProtectionManager--) | รับผู้จัดการสิทธิ์สำหรับการนำเสนอนี้ |
| [getSlides()](#getSlides--) | คืนรายการสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ |
| [getSections()](#getSections--) | คืนรายการส่วนของสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ |
| [getSlideSize()](#getSlideSize--) | คืนอ็อบเจกต์ขนาดสไลด์ |
| [getNotesSize()](#getNotesSize--) | คืนอ็อบเจกต์ขนาดสไลด์โน้ต |
| [getLayoutSlides()](#getLayoutSlides--) | คืนรายการสไลด์เลย์เอาต์ทั้งหมดที่กำหนดไว้ในการนำเสนอ |
| [getMasters()](#getMasters--) | คืนรายการสไลด์มาสเตอร์ทั้งหมดที่กำหนดไว้ในการนำเสนอ |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | คืนผู้จัดการโน้ตมาสเตอร์ |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | คืนผู้จัดการแฮนด์เอาต์มาสเตอร์ |
| [getFontsManager()](#getFontsManager--) | คืนผู้จัดการฟอนต์ |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | คืนสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง |
| [getCommentAuthors()](#getCommentAuthors--) | คืนคอลเลกชันของผู้เขียนความคิดเห็น |
| [getDocumentProperties()](#getDocumentProperties--) | คืนอ็อบเจกต์ DocumentProperties ที่บรรจุคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร |
| [getImages()](#getImages--) | คืนคอลเลกชันของรูปภาพทั้งหมดในการนำเสนอ |
| [getAudios()](#getAudios--) | คืนคอลเลกชันของไฟล์เสียงฝังทั้งหมดในการนำเสนอ |
| [getVideos()](#getVideos--) | คืนคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในการนำเสนอ |
| [getCustomData()](#getCustomData--) | คืนข้อมูลกำหนดเองของการนำเสนอ |
| [getVbaProject()](#getVbaProject--) | รับโครงการ VBA ที่มีแมโครการนำเสนอ |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | รับโครงการ VBA ที่มีแมโครการนำเสนอ |
| [getSourceFormat()](#getSourceFormat--) | คืนข้อมูลเกี่ยวกับรูปแบบที่การนำเสนอถูกโหลด |
| [getMasterTheme()](#getMasterTheme--) | คืนธีมมาสเตอร์ของการนำเสนอ |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์การนำเสนอ (ไม่รวมสไลด์มาสเตอร์, เลย์เอาต์, โน้ต) อย่างง่าย |
| [getViewProperties()](#getViewProperties--) | รับคุณสมบัตุมุมมองทั่วการนำเสนอ |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | คืนส่วนข้อมูลกำหนดเองทั้งหมดในการนำเสนอ |
| [getDigitalSignatures()](#getDigitalSignatures--) | คืนคอลเลกชันของลายเซ็นที่ใช้ในการลงนามการนำเสนอ |
| [getSensitivityLabels()](#getSensitivityLabels--) | คืนคอลเลกชันของป้ายความสำคัญที่ใช้กับเอกสารการนำเสนอ |
| [save(String fname, int format)](#save-java.lang.String-int-) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุ |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุและตัวเลือกเพิ่มเติม |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | บันทึกสไลด์ที่ระบุของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุ |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ที่ระบุของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุ |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังชุดไฟล์ที่เป็น XAML markup |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอ |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | คืนอ็อบเจกต์ Thumbnail IImage สำหรับสไลด์ที่ระบุของการนำเสนอ |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยการปรับสเกลที่กำหนดเอง |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยการปรับสเกลที่กำหนดเอง |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยขนาดที่กำหนด |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยขนาดที่กำหนด |
| [getSlideById(long id)](#getSlideById-long-) | คืน Slide, MasterSlide หรือ LayoutSlide ตาม Id |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่ยอมรับทั้งหมดในทุกสไลด์ |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | ไฮไลต์ทุกการจับคู่ของ regular expression ด้วยสีที่ระบุ |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | แทนที่ทุกการจับคู่ของ regular expression ด้วยสตริงที่ระบุ |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

คืนค่า或กำหนดวันและเวลาที่จะใช้แทนเนื้อหาของฟิลด์วันเวลา เวลาโดยปริยายของการสร้างออบเจกต์ Presentation นี้โดยค่าเริ่มต้น อ่าน/เขียน java.util.Date.

**คืนค่า:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

คืนค่า或กำหนดวันและเวลาที่จะใช้แทนเนื้อหาของฟิลด์วันเวลา เวลาโดยปริยายของการสร้างออบเจกต์ Presentation นี้โดยค่าเริ่มต้น อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของการนำเสนอ อ่านอย่างเดียว [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**คืนค่า:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

รับผู้จัดการสิทธิ์สำหรับการนำเสนอนี้ อ่านอย่างเดียว [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**คืนค่า:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

คืนรายการสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ อ่านอย่างเดียว [ISlideCollection](../../com.aspose.slides/islidecollection).

**คืนค่า:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

คืนรายการส่วนของสไลด์ทั้งหมดที่กำหนดไว้ในการนำเสนอ อ่านอย่างเดียว [ISectionCollection](../../com.aspose.slides/isectioncollection).

**คืนค่า:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

คืนอ็อบเจกต์ขนาดสไลด์ อ่านอย่างเดียว [ISlideSize](../../com.aspose.slides/islidesize).

**คืนค่า:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

คืนอ็อบเจกต์ขนาดสไลด์โน้ต อ่านอย่างเดียว [INotesSize](../../com.aspose.slides/inotessize).

**คืนค่า:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

คืนรายการสไลด์เลย์เอาต์ทั้งหมดที่กำหนดไว้ในการนำเสนอ อ่านอย่างเดียว [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

คุณสามารถเข้าถึง API แทนสำหรับการเพิ่ม/แทรก/ลบ/คัดลอกสไลด์เลย์เอาต์โดยใช้คุณสมบัติ IMasterSlide.LayoutSlides

**คืนค่า:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

คืนรายการสไลด์มาสเตอร์ทั้งหมดที่กำหนดไว้ในการนำเสนอ อ่านอย่างเดียว [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**คืนค่า:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

คืนผู้จัดการโน้ตมาสเตอร์ อ่านอย่างเดียว [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**คืนค่า:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

คืนผู้จัดการแฮนด์เอาต์มาสเตอร์ อ่านอย่างเดียว [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**คืนค่า:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

คืนผู้จัดการฟอนต์ อ่านอย่างเดียว [IFontsManager](../../com.aspose.slides/ifontsmanager).

**คืนค่า:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

คืนสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

คืนคอลเลกชันของผู้เขียนความคิดเห็น อ่านอย่างเดียว [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**คืนค่า:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

คืนอ็อบเจกต์ DocumentProperties ที่บรรจุคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร อ่านอย่างเดียว [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**คืนค่า:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

คืนคอลเลกชันของรูปภาพทั้งหมดในการนำเสนอ อ่านอย่างเดียว [IImageCollection](../../com.aspose.slides/iimagecollection).

**คืนค่า:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

คืนคอลเลกชันของไฟล์เสียงฝังทั้งหมดในการนำเสนอ อ่านอย่างเดียว [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**คืนค่า:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

คืนคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในการนำเสนอ อ่านอย่างเดียว [IVideoCollection](../../com.aspose.slides/ivideocollection).

**คืนค่า:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

คืนข้อมูลกำหนดเองของการนำเสนอ อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**คืนค่า:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

รับโครงการ VBA ที่มีแมโครการนำเสนอ อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject).

**คืนค่า:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

รับโครงการ VBA ที่มีแมโครการนำเสนอ อ่าน/เขียน [IVbaProject](../../com.aspose.slides/ivbaproject).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

คืนข้อมูลเกี่ยวกับรูปแบบที่การนำเสนอถูกโหลด อ่านอย่างเดียว [SourceFormat](../../com.aspose.slides/sourceformat).

**คืนค่า:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

คืนธีมมาสเตอร์ของการนำเสนอ อ่านอย่างเดียว [IMasterTheme](../../com.aspose.slides/imastertheme).

**คืนค่า:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์การนำเสนอ (ไม่รวมสไลด์มาสเตอร์, เลย์เอาต์, โน้ต) อย่างง่าย อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**คืนค่า:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

รับคุณสมบัตุมุมมองทั่วการนำเสนอ อ่านอย่างเดียว [IViewProperties](../../com.aspose.slides/iviewproperties).

**คืนค่า:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

แสดงหมายเลขสไลด์แรกในการนำเสนอ อ่าน/เขียน int.

**คืนค่า:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

แสดงหมายเลขสไลด์แรกในการนำเสนอ อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

คืนส่วนข้อมูลกำหนดเองทั้งหมดในการนำเสนอ อ่านอย่างเดียว ICustomXmlPart[].

**คืนค่า:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

คืนคอลเลกชันของลายเซ็นที่ใช้ในการลงนามการนำเสนอ อ่านอย่างเดียว [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

คืนคอลเลกชันของป้ายความสำคัญที่ใช้กับเอกสารการนำเสนอ อ่านอย่างเดียว [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // แสดงป้ายที่ใช้
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // เพิ่มป้ายใหม่
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // ดึง Id ของป้ายความละเอียดจากนโยบาย
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

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุและตัวเลือกเพิ่มเติม

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังชุดไฟล์ที่เป็น XAML markup

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | The XAML format options. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**คืนค่า:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

คืนอ็อบเจกต์ Thumbnail IImage สำหรับสไลด์ที่ระบุของการนำเสนอ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |

**คืนค่า:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยการปรับสเกลที่กำหนดเอง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**คืนค่า:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยการปรับสเกลที่กำหนดเอง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**คืนค่า:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยขนาดที่กำหนด

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**คืนค่า:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยขนาดที่กำหนด

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**คืนค่า:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

คืน Slide, MasterSlide หรือ LayoutSlide ตาม Id

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id of a slide. |

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่ยอมรับทั้งหมดในทุกสไลด์

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // เน้นข้อความ 'the' ที่แยกจากกันทั้งหมด
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

ไฮไลต์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // เน้นข้อความ 'the' ที่แยกจากกันทั้งหมด
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text search options [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

ไฮไลต์ทุกการจับคู่ของ regular expression ด้วยสีที่ระบุ

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // เน้นข้อความ 'the' ที่แยกจากกันทั้งหมด
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | The regular expression java.util.regex.Pattern to get strings to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ

--------------------

> ```
> ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการแทนที่สตริงที่ระบุหนึ่งด้วยสตริงที่ระบุอีกสตริงหนึ่ง.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การปรากฏของ 'the' ที่แยกกันทั้งหมดด้วย '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | The string to be replaced. |
| newText | java.lang.String | The string to replace all occurrences of oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text search options [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

แทนที่ทุกการจับคู่ของ regular expression ด้วยสตริงที่ระบุ

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // แทนที่การปรากฏของ 'the' ที่แยกกันทั้งหมดด้วย '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | The regular expression java.util.regex.Pattern to get strings to replace. |
| newText | java.lang.String | The string to replace all occurrences of the strings to be replaced. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
