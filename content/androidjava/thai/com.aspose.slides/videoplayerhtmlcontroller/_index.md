---
title: VideoPlayerHtmlController
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: คลาสนี้อนุญาตให้ส่งออกไฟล์วิดีโอและเสียงเป็น HTML
type: docs
url: /th/com.aspose.slides/videoplayerhtmlcontroller/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซทั้งหมดที่นำไปใช้:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

คลาสนี้อนุญาตให้ส่งออกไฟล์วิดีโอและเสียงเป็น HTML
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ใหม่ของตัวควบคุม |
## เมธอด

| เมธอด | คำอธิบาย |
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

สร้างอินสแตนซ์ใหม่ของตัวควบคุม

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางที่ไฟล์วิดีโอและเสียงจะถูกสร้างขึ้น |
| fileName | java.lang.String | ชื่อของไฟล์ HTML |
| baseUri | java.lang.String | URI พื้นฐานที่ใช้สำหรับสร้างลิงก์ |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

ถูกเรียกเพื่อเขียนส่วนหัวของเอกสาร HTML จะถูกเรียกหนึ่งครั้งต่อการแปลงพรีเซนเทชั่น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

ถูกเรียกเพื่อเขียนส่วนท้ายของเอกสาร HTML จะถูกเรียกหนึ่งครั้งต่อการแปลงพรีเซนเทชั่น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

ถูกเรียกเพื่อเขียนส่วนหัวของสไลด์ HTML จะถูกเรียกหนึ่งครั้งต่อแต่ละสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

ถูกเรียกเพื่อเขียนส่วนท้ายของสไลด์ HTML จะถูกเรียกหนึ่งครั้งต่อแต่ละสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

ถูกเรียกก่อนการเรนเดอร์ของรูปทรง จะถูกเรียกหนึ่งครั้งต่อแต่ละรูปทรง หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะสิ้นสุด ส่วนของ HTML ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นบนภาพก่อนหน้า

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

ถูกเรียกก่อนการเรนเดอร์ของรูปทรง จะถูกเรียกหนึ่งครั้งต่อแต่ละรูปทรง หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะสิ้นสุด ส่วนของ HTML ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นบนภาพก่อนหน้า

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```

ฟังก์ชันนี้ถูกเรียกก่อนการเรนเดอร์รูปทรงเป็น SVG เพื่อให้ผู้ใช้ควบคุม SVG ที่ได้

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

กำหนดตำแหน่งที่วัตถุควรจัดเก็บ วิธีนี้จะถูกเรียกหนึ่งครั้งต่อแต่ละ id ของวัตถุ ไม่รับประกันว่าจะไม่มีวัตถุสองอันที่มีข้อมูล semanticName และ contentType เดียวกันแต่ id ต่างกัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**คืนค่า:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```

คืนค่า URL ไปยังวัตถุภายนอก วิธีนี้จะถูกเรียกเสมอหาก \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) คืนค่า [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) และอาจถูกเรียกหาก \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) คืนค่า [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) แต่การฝังไม่เป็นไปได้ สามารถเรียกได้หลายครั้งสำหรับ id ของวัตถุเดียวกัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**คืนค่า:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```

บันทึกวัตถุภายนอก

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
