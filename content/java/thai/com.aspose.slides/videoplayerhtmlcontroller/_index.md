---
title: VideoPlayerHtmlController
second_title: Aspose.Slides สำหรับ Java API Reference
description: คลาสนี้อนุญาตให้ส่งออกไฟล์วิดีโอและเสียงเป็น HTML
type: docs
url: /th/com.aspose.slides/videoplayerhtmlcontroller/
---
**Inheritance:**
การสืบทอด:

**All Implemented Interfaces:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

คลาสนี้อนุญาตให้ส่งออกไฟล์วิดีโอและเสียงเป็น HTML
## Constructors

| Constructor | Description |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ใหม่ของ controller |
## Methods

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |
### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```


สร้างอินสแตนซ์ใหม่ของ controller

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางที่ไฟล์วิดีโอและเสียงจะถูกสร้าง |
| fileName | java.lang.String | ชื่อไฟล์ HTML |
| baseUri | java.lang.String | URI พื้นฐานที่ใช้สำหรับการสร้างลิงก์ |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


เรียกเพื่อเขียนส่วนหัวของเอกสาร html. เรียกหนึ่งครั้งต่อการแปลงพรีเซนเทชัน

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


เรียกเพื่อเขียนส่วนท้ายของเอกสาร html. เรียกหนึ่งครั้งต่อการแปลงพรีเซนเทชัน

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


เรียกเพื่อเขียนส่วนหัวของสไลด์ html. เรียกหนึ่งครั้งต่อแต่ละสไลด์

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


เรียกเพื่อเขียนส่วนท้ายของสไลด์ html. เรียกหนึ่งครั้งต่อแต่ละสไลด์

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


เรียกก่อนการเรนเดอร์ของ shape. เรียกหนึ่งครั้งต่อแต่ละ shape. หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสมบูรณ์, fragment html ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มเหนือภาพก่อนหน้า

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


เรียกก่อนการเรนเดอร์ของ shape. เรียกหนึ่งครั้งต่อแต่ละ shape. หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสมบูรณ์, fragment html ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มเหนือภาพก่อนหน้า

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


ฟังก์ชันนี้ถูกเรียกก่อนการเรนเดอร์ shape เป็น SVG เพื่อให้ผู้ใช้ควบคุม SVG ที่ได้

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


กำหนดว่าควรจัดเก็บ object ที่ใด วิธีนี้จะถูกเรียกหนึ่งครั้งต่อแต่ละ object id. ไม่รับประกันว่าจะไม่มี object สองอันที่มี data, semanticName และ contentType เดียวกันแต่มี id ต่างกัน

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**Returns:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


ผลลัพธ์: URL ไปยัง object ภายนอก. วิธีนี้จะถูกเรียกเสมอหาก \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) คืนค่า [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) และอาจถูกเรียกหาก \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) คืนค่า [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) แต่ไม่สามารถฝังได้. สามารถเรียกหลายครั้งสำหรับ object id เดียวกัน

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**Returns:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


บันทึก object ภายนอก

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
