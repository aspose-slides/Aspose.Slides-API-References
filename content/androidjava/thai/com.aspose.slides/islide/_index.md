---
title: ISlide
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงถึงสไลด์ในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/islide/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

แสดงสไลด์ในงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์. |
| [getSlideNumber()](#getSlideNumber--) | ส่งคืนจำนวนสไลด์. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | ส่งคืนจำนวนสไลด์. |
| [getHidden()](#getHidden--) | กำหนดว่าสไลด์ที่ระบุจะถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. |
| [setHidden(boolean value)](#setHidden-boolean-) | กำหนดว่าสไลด์ที่ระบุจะถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | ส่งคืนอ็อบเจ็กต์ภาพที่มีการสเกลแบบกำหนดเอง. |
| [getImage()](#getImage--) | ส่งคืนอ็อบเจ็กต์ภาพขนาดย่อ (20% ของขนาดจริง). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | ส่งคืนอ็อบเจ็กต์ภาพที่มีขนาดที่ระบุ. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | ส่งคืนอ็อบเจ็กต์ bitmap tiff ขนาดย่อที่มีพารามิเตอร์ที่ระบุ. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | ส่งคืนอ็อบเจ็กต์ Bitmap ขนาดย่อ. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | ส่งคืนอ็อบเจ็กต์ Bitmap ขนาดย่อที่มีการสเกลแบบกำหนดเอง. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | ส่งคืนอ็อบเจ็กต์ Bitmap ขนาดย่อที่มีขนาดที่ระบุ. |
| [getLayoutSlide()](#getLayoutSlide--) | ส่งคืนหรือกำหนดสไลด์เค้าโครงสำหรับสไลด์ปัจจุบัน. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | ส่งคืนหรือกำหนดสไลด์เค้าโครงสำหรับสไลด์ปัจจุบัน. |
| [getNotesSlideManager()](#getNotesSlideManager--) | อนุญาตให้เข้าถึงสไลด์บันทึก, เพิ่มและลบได้. |
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

**คืนค่า:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

ส่งคืนจำนวนสไลด์. ดัชนีของสไลด์ในคอลเลกชัน [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) เสมอเท่ากับ SlideNumber - 1. อ่าน/เขียน int.

**คืนค่า:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

ส่งคืนจำนวนสไลด์. ดัชนีของสไลด์ในคอลเลกชัน [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) เสมอเท่ากับ SlideNumber - 1. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

กำหนดว่าสไลด์ที่ระบุจะถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

กำหนดว่าสไลด์ที่ระบุจะถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

ส่งคืนอ็อบเจ็กต์ภาพที่มีการสเกลแบบกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| scaleX | float | ค่าที่ใช้สเกล Thumbnail นี้ในแนวแกน x. |
| scaleY | float | ค่าที่ใช้สเกล Thumbnail นี้ในแนวแกน y. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Image android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

ส่งคืนอ็อบเจ็กต์ภาพขนาดย่อ (20% ของขนาดจริง).

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Image android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

ส่งคืนอ็อบเจ็กต์ภาพที่มีขนาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | ขนาดของภาพที่จะสร้าง. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Bitmap.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

ส่งคืนอ็อบเจ็กต์ bitmap tiff ขนาดย่อที่มีพารามิเตอร์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | ตัวเลือก Tiff. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Image.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

ส่งคืนอ็อบเจ็กต์ Bitmap ขนาดย่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการ Rendering. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Bitmap.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

ส่งคืนอ็อบเจ็กต์ Bitmap ขนาดย่อที่มีการสเกลแบบกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการ Rendering. |
| scaleX | float | ค่าที่ใช้สเกล Thumbnail นี้ในแนวแกน x. |
| scaleY | float | ค่าที่ใช้สเกล Thumbnail นี้ในแนวแกน y. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Bitmap.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

ส่งคืนอ็อบเจ็กต์ Bitmap ขนาดย่อที่มีขนาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการ Rendering. |
| imageSize | [Size](../../com.aspose.slides.android/size) | ขนาดของภาพที่จะสร้าง. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Bitmap.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

ส่งคืนหรือกำหนดสไลด์เค้าโครงสำหรับสไลด์ปัจจุบัน. อ่าน/เขียน [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**คืนค่า:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

ส่งคืนหรือกำหนดสไลด์เค้าโครงสำหรับสไลด์ปัจจุบัน. อ่าน/เขียน [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

อนุญาตให้เข้าถึงสไลด์บันทึก, เพิ่มและลบได้. อ่านอย่างเดียว [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**คืนค่า:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

ส่งคืนคอมเมนต์สไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | ผู้เขียนของคอมเมนต์ที่จะค้นหา หรือ null เพื่อส่งคืนคอมเมนต์ทั้งหมด. |

**คืนค่า:**
com.aspose.slides.IComment[] - อาร์เรย์ของ [IComment](../../com.aspose.slides/icomment).

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | ตัวเลือกการสร้าง SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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