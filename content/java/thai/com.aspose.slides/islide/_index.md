---
title: ISlide
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนสไลด์ในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/islide/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

เป็นตัวแทนสไลด์ในงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์. |
| [getSlideNumber()](#getSlideNumber--) | ส่งคืนหมายเลขของสไลด์. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | ส่งคืนหมายเลขของสไลด์. |
| [getHidden()](#getHidden--) | กำหนดว่าหนึ่งสไลด์ที่ระบุถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. |
| [setHidden(boolean value)](#setHidden-boolean-) | กำหนดว่าหนึ่งสไลด์ที่ระบุถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | ส่งคืนวัตถุ Image ที่มีการปรับสเกลแบบกำหนดเอง. |
| [getImage()](#getImage--) | ส่งคืนวัตถุ Thumbnail Image (20% ของขนาดจริง). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | ส่งคืนวัตถุ Image ที่มีขนาดที่ระบุ. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | ส่งคืนวัตถุ Thumbnail tiff bitmap ที่มีพารามิเตอร์ที่ระบุ. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | ส่งคืนวัตถุ Thumbnail Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | ส่งคืนวัตถุ Thumbnail Bitmap ที่มีการปรับสเกลแบบกำหนดเอง. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | ส่งคืนวัตถุ Thumbnail Bitmap ที่มีขนาดที่ระบุ. |
| [getLayoutSlide()](#getLayoutSlide--) | ส่งคืนหรือกำหนดสไลด์เลเอาต์สำหรับสไลด์ปัจจุบัน. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | ส่งคืนหรือกำหนดสไลด์เลเอาต์สำหรับสไลด์ปัจจุบัน. |
| [getNotesSlideManager()](#getNotesSlideManager--) | อนุญาตให้เข้าถึงสไลด์บันทึกย่อ, เพิ่มและลบมัน. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | ส่งคืนคอมเมนต์สไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF. |
| [remove()](#remove--) | ลบสไลด์ออกจากงานนำเสนอ. |
| [reset()](#reset--) | รีเซ็ตตำแหน่ง, ขนาดและการจัดรูปแบบของทุกรูปร่างที่มีต้นแบบบน LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

ส่งคืนผู้จัดการ HeaderFooter ของสไลด์. อ่านอย่างเดียว [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**ส่งคืน:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

ส่งคืนหมายเลขของสไลด์. ดัชนีของสไลด์ในคอลเลกชัน [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) จะเท่ากับ SlideNumber - 1 เสมอ. อ่าน/เขียน int.

**ส่งคืน:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

ส่งคืนหมายเลขของสไลด์. ดัชนีของสไลด์ในคอลเลกชัน [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) จะเท่ากับ SlideNumber - 1 เสมอ. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

กำหนดว่าหนึ่งสไลด์ที่ระบุถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

กำหนดว่าหนึ่งสไลด์ที่ระบุถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

ส่งคืนวัตถุ Image ที่มีการปรับสเกลแบบกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scaleX | float | ค่าที่ใช้ปรับขนาด Thumbnail นี้ในแนวแกน x. |
| scaleY | float | ค่าที่ใช้ปรับขนาด Thumbnail นี้ในแนวแกน y. |

**ส่งคืน:**
[IImage](../../com.aspose.slides/iimage) - วัตถุ Image java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

ส่งคืนวัตถุ Thumbnail Image (20% ของขนาดจริง).

**ส่งคืน:**
[IImage](../../com.aspose.slides/iimage) - วัตถุ Image java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

ส่งคืนวัตถุ Image ที่มีขนาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageSize | java.awt.Dimension | ขนาดของภาพที่จะสร้าง. |

**ส่งคืน:**
[IImage](../../com.aspose.slides/iimage) - วัตถุ Bitmap.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

ส่งคืนวัตถุ Thumbnail tiff bitmap ที่มีพารามิเตอร์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | ตัวเลือก Tiff. |

**ส่งคืน:**
[IImage](../../com.aspose.slides/iimage) - วัตถุ Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

ส่งคืนวัตถุ Thumbnail Bitmap.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |

**ส่งคืน:**
[IImage](../../com.aspose.slides/iimage) - วัตถุ Bitmap.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

ส่งคืนวัตถุ Thumbnail Bitmap ที่มีการปรับสเกลแบบกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| scaleX | float | ค่าที่ใช้ปรับขนาด Thumbnail นี้ในแนวแกน x. |
| scaleY | float | ค่าที่ใช้ปรับขนาด Thumbnail นี้ในแนวแกน y. |

**ส่งคืน:**
[IImage](../../com.aspose.slides/iimage) - วัตถุ Bitmap.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

ส่งคืนวัตถุ Thumbnail Bitmap ที่มีขนาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| imageSize | java.awt.Dimension | ขนาดของภาพที่จะสร้าง. |

**ส่งคืน:**
[IImage](../../com.aspose.slides/iimage) - วัตถุ Bitmap.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

ส่งคืนหรือกำหนดสไลด์เลเอาต์สำหรับสไลด์ปัจจุบัน. อ่าน/เขียน [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**ส่งคืน:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

ส่งคืนหรือกำหนดสไลด์เลเอาต์สำหรับสไลด์ปัจจุบัน. อ่าน/เขียน [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

อนุญาตให้เข้าถึงสไลด์บันทึกย่อ, เพิ่มและลบมัน. อ่านอย่างเดียว [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**ส่งคืน:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

ส่งคืนคอมเมนต์สไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | ผู้เขียนของคอมเมนต์ที่ต้องการค้นหา หรือ null เพื่อส่งคืนคอมเมนต์ทั้งหมด. |

**ส่งคืน:**
com.aspose.slides.IComment[] - อาเรย์ของ [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | ตัวเลือกการสร้าง SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
### remove() {#remove--}
```
public abstract void remove()
```

ลบสไลด์ออกจากงานนำเสนอ.
### reset() {#reset--}
```
public abstract void reset()
```

รีเซ็ตตำแหน่ง, ขนาดและการจัดรูปแบบของทุกรูปร่างที่มีต้นแบบบน LayoutSlide.