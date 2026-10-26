---
title: Slide
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของสไลด์ในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/slide/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

เป็นตัวแทนของสไลด์ในงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์. |
| [getThemeManager()](#getThemeManager--) | คืนค่า overriding theme manager. |
| [getSlideNumber()](#getSlideNumber--) | คืนค่าจำนวนของสไลด์. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | คืนค่าจำนวนของสไลด์. |
| [getHidden()](#getHidden--) | ตรวจสอบว่าสไลด์ที่ระบุถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. |
| [setHidden(boolean value)](#setHidden-boolean-) | ตรวจสอบว่าสไลด์ที่ระบุถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่า shapes บน master slide ควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่า shapes บน master slide ควรแสดงบนสไลด์หรือไม่. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | คืนค่า Thumbnail Image object ที่มีการสเกลแบบกำหนดเอง. |
| [getImage()](#getImage--) | คืนค่า Thumbnail Image object (20% ของขนาดจริง). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | คืนค่า Thumbnail Image object ที่มีขนาดที่ระบุ. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | คืนค่า Thumbnail tiff image object ที่มีพารามิเตอร์ที่ระบุ. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | คืนค่า Thumbnail Image object. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | คืนค่า Thumbnail Image object ที่มีการสเกลแบบกำหนดเอง. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | คืนค่า Thumbnail Image object ที่มีขนาดที่ระบุ. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF. |
| [remove()](#remove--) | ลบสไลด์ออกจากงานนำเสนอ. |
| [getLayoutSlide()](#getLayoutSlide--) | คืนค่าหรือกำหนด layout slide สำหรับสไลด์ปัจจุบัน. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | คืนค่าหรือกำหนด layout slide สำหรับสไลด์ปัจจุบัน. |
| [reset()](#reset--) | รีเซ็ตตำแหน่ง ขนาด และการจัดรูปแบบของทุก shape ที่มี prototype บน LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | อนุญาตให้เข้าถึง notes slide, เพิ่มและลบ. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | คืนค่าความคิดเห็นสไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวม runs ที่มีการจัดรูปแบบเดียวกันในทุก paragraph ใน shape ที่รับได้ทั้งหมด. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของสไลด์. อ่านอย่างเดียว [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**คืนค่า:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

คืนค่า overriding theme manager. อ่านอย่างเดียว [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**คืนค่า:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

คืนค่าจำนวนของสไลด์. ดัชนีของสไลด์ในคอลเลกชัน [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) จะเท่ากับ SlideNumber - Presentation.FirstSlideNumber เสมอ. อ่าน/เขียน int.

**คืนค่า:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

คืนค่าจำนวนของสไลด์. ดัชนีของสไลด์ในคอลเลกชัน [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) จะเท่ากับ SlideNumber - Presentation.FirstSlideNumber เสมอ. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

กำหนดว่สไลด์ที่ระบุถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

กำหนดว่สไลด์ที่ระบุถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

ระบุว่า shapes บน master slide ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

ระบุว่า shapes บน master slide ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

คืนค่า Thumbnail Image object ที่มีการสเกลแบบกำหนดเอง.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // เข้าถึงสไลด์แรก
>      ISlide sld = pres.getSlides().get_Item(0);
>      // สร้างภาพเต็มสเกล
>      IImage bmp = sld.getImage(1f, 1f);
>      // บันทึกภาพลงดิสก์ในรูปแบบ JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // แปลงสไลด์แรกในงานนำเสนอเป็นอ็อบเจกต์ Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // บันทึกภาพในรูปแบบ PNG
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // สร้างภาพเต็มสเกล
>          IImage bmp = sld.getImage(1f, 1f);
>          // บันทึกภาพลงดิสก์ในรูปแบบ JPEG
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // กำหนดมิติ
>      int desiredX = 1200;
>      int desiredY = 800;
>      // รับค่าที่สเกลของ X และ Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // สร้างภาพเต็มสเกล
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // บันทึกภาพลงดิสก์ในรูปแบบ JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scaleX | float | ค่าที่ใช้ในการสเกล Thumbnail นี้ในแนวแกน x. |
| scaleY | float | ค่าที่ใช้ในการสเกล Thumbnail นี้ในแนวแกน y. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ IImage.
### getImage() {#getImage--}
```
public final IImage getImage()
```

คืนค่า Thumbnail Image object (20% ของขนาดจริง).

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

คืนค่า Thumbnail Image object ที่มีขนาดที่ระบุ.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // แปลงสไลด์แรกในงานนำเสนอเป็น Bitmap ด้วยขนาดที่ระบุ
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // บันทึกภาพในรูปแบบ JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageSize | java.awt.Dimension | ขนาดของภาพที่จะสร้าง. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Image.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

คืนค่า Thumbnail tiff image object ที่มีพารามิเตอร์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | ตัวเลือก Tiff. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

คืนค่า Thumbnail Image object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Image.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

คืนค่า Thumbnail Image object ที่มีการสเกลแบบกำหนดเอง.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // สร้างตัวเลือกการเรนเดอร์
>      IRenderingOptions options = new RenderingOptions();
>      // สร้างตัวเลือกการจัดวางโน้ตและความคิดเห็น
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // กำหนดตำแหน่งของโน้ตบนหน้า
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // กำหนดตำแหน่งของความคิดเห็นบนหน้า
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // กำหนดความกว้างของพื้นที่แสดงความคิดเห็น
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // กำหนดสีสำหรับพื้นที่ความคิดเห็น
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // ตั้งค่าตัวเลือกการจัดวางสำหรับการเรนเดอร์
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // แปลงสไลด์แรกของงานนำเสนอเป็นอ็อบเจกต์ BufferedImage
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // บันทึกภาพในรูปแบบ GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| scaleX | float | ค่าที่ใช้ในการสเกล Thumbnail นี้ในแนวแกน x. |
| scaleY | float | ค่าที่ใช้ในการสเกล Thumbnail นี้ในแนวแกน y. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Bitmap.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

คืนค่า Thumbnail Image object ที่มีขนาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| imageSize | java.awt.Dimension | ขนาดของภาพที่จะสร้าง. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - อ็อบเจ็กต์ Image.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // บันทึกสไลด์แรกเป็นไฟล์ SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // บันทึกสไลด์แรกเป็นไฟล์ SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | ตัวเลือกการสร้าง SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // บันทึกสไลด์แรกเป็นไฟล์เมต้า
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
### remove() {#remove--}
```
public final void remove()
```

ลบสไลด์ออกจากงานนำเสนอ.
### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

คืนค่าหรือกำหนด layout slide สำหรับสไลด์ปัจจุบัน. อ่าน/เขียน [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**คืนค่า:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

คืนค่าหรือกำหนด layout slide สำหรับสไลด์ปัจจุบัน. อ่าน/เขียน [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```

รีเซ็ตตำแหน่ง ขนาด และการจัดรูปแบบของทุก shape ที่มี prototype บน LayoutSlide.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

อนุญาตให้เข้าถึง notes slide, เพิ่มและลบ. อ่านอย่างเดียว [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**คืนค่า:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

คืนค่าความคิดเห็นสไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | ผู้เขียนของความคิดเห็นที่ต้องการค้นหา หรือ null เพื่อคืนความคิดเห็นทั้งหมด. |

**คืนค่า:**
com.aspose.slides.IComment[] - อาเรย์ของ [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

รวม runs ที่มีการจัดรูปแบบเดียวกันในทุก paragraph ใน shape ที่รับได้ทั้งหมด.