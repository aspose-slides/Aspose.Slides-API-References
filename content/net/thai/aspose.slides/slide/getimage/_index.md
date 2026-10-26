---
title: GetImage
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: คืนค่าอ็อบเจ็กต์ Image ขนาดย่อพร้อมการปรับสเกลแบบกำหนดเอง.
type: docs
weight: 80
url: /th/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

คืนค่าอ็อบเจ็กต์ Image ขนาดย่อพร้อมการปรับสเกลแบบกำหนดเอง.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scaleX | Single | ค่าที่ใช้ในการปรับสเกล Thumbnail นี้ในแนวแกน x |
| scaleY | Single | ค่าที่ใช้ในการปรับสเกล Thumbnail นี้ในแนวแกน y |

### ค่าที่ส่งกลับ

IImage object.

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการสร้างภาพย่อจาก PowerPoint Presentation.

```csharp
[C#]
// สร้างอ็อบเจ็กต์ Presentation ที่แทนไฟล์การนำเสนอ
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // เข้าถึงสไลด์แรก
    ISlide sld = pres.Slides[0];
    // สร้างภาพขนาดเต็ม
    IImage bmp = sld.GetImage(1f, 1f);
    // บันทึกภาพลงดิสก์ในรูปแบบ JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีการแปลงสไลด์เป็นบิตแมปและบันทึกรูปภาพเป็น PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // แปลงสไลด์แรกในพรีเซนเทชันเป็นอ็อบเจ็กต์ Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // บันทึกรูปภาพในรูปแบบ PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

ตัวอย่างต่อไปนี้แสดงวิธีการแปลง PowerPoint PPT/PPTX เป็น JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// สร้างภาพขนาดเต็ม
		IImage bmp = sld.GetImage(1f, 1f);
		// บันทึกรูปภาพลงดิสก์ในรูปแบบ JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

ตัวอย่างต่อไปนี้แสดงวิธีการแปลง PowerPoint PPT/PPTX เป็น JPG พร้อมขนาดที่กำหนดเอง.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// กำหนดมิติ
	int desiredX = 1200;
	int desiredY = 800;
	// รับค่า X และ Y ที่ปรับสเกลแล้ว
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// สร้างภาพขนาดเต็ม
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// บันทึกรูปภาพลงดิสก์ในรูปแบบ JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IImage](../../iimage)
* คลาส [Slide](../../slide)
* เนมสเปซ [Aspose.Slides](../../slide)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

คืนค่าอ็อบเจ็กต์ Image ขนาดย่อ (20% ของขนาดจริง).

```csharp
public IImage GetImage()
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IImage](../../iimage)
* คลาส [Slide](../../slide)
* เนมสเปซ [Aspose.Slides](../../slide)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

คืนค่าอ็อบเจ็กต์ Image ขนาดย่อพร้อมขนาดที่ระบุ.

```csharp
public IImage GetImage(Size imageSize)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageSize | Size | ขนาดของรูปภาพที่ต้องการสร้าง |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Image.

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการแปลงสไลด์เป็นรูปภาพด้วยขนาดที่กำหนดเองโดยใช้ C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // แปลงสไลด์แรกในพรีเซนเทชันเป็น Bitmap ด้วยขนาดที่ระบุ
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // บันทึกรูปภาพในรูปแบบ JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IImage](../../iimage)
* คลาส [Slide](../../slide)
* เนมสเปซ [Aspose.Slides](../../slide)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

คืนค่าอ็อบเจ็กต์ภาพ tiff ขนาดย่อพร้อมพารามิเตอร์ที่ระบุ.

```csharp
public IImage GetImage(ITiffOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | ITiffOptions | ตัวเลือก Tiff |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Image.

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| InvalidOperationException | เกิดขึ้นเมื่อ options.SlideLayoutOption เป็น NotesCommentsLayoutingOptions และคุณสมบัติ NotesPosition มีค่า NotesPositions.BottomFull. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IImage](../../iimage)
* อินเทอร์เฟซ [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* คลาส [Slide](../../slide)
* เนมสเปซ [Aspose.Slides](../../slide)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

คืนค่าอ็อบเจ็กต์ Image ขนาดย่อ.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | IRenderingOptions | ตัวเลือกการเรนเดอร์ |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Image.

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| InvalidOperationException | เกิดขึ้นเมื่อ notesCommentsLayouting.NotesPosition มีค่า NotesPositions.BottomFull |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IImage](../../iimage)
* อินเทอร์เฟซ [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* คลาส [Slide](../../slide)
* เนมสเปซ [Aspose.Slides](../../slide)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

คืนค่าอ็อบเจ็กต์ Image ขนาดย่อพร้อมการปรับสเกลแบบกำหนดเอง.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | IRenderingOptions | ตัวเลือกการเรนเดอร์ |
| scaleX | Single | ค่าที่ใช้ในการปรับสเกล Thumbnail นี้ในแนวแกน x |
| scaleY | Single | ค่าที่ใช้ในการปรับสเกล Thumbnail นี้ในแนวแกน y |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Bitmap.

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| InvalidOperationException | เกิดขึ้นเมื่อ notesCommentsLayouting.NotesPosition มีค่า NotesPositions.BottomFull |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการแปลงสไลด์พร้อมบันทึกย่อและความคิดเห็นเป็นรูปภาพโดยใช้ C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // สร้างตัวเลือกการเรนเดอร์
    IRenderingOptions options = new RenderingOptions();
    // สร้างตัวเลือกการจัดวางบันทึกย่อและความคิดเห็น
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // กำหนดตำแหน่งของบันทึกย่อในหน้า
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // กำหนดตำแหน่งของความคิดเห็นในหน้า
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // กำหนดความกว้างของพื้นที่แสดงความคิดเห็น
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // กำหนดสีของพื้นที่ความคิดเห็น
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // ตั้งค่าตัวเลือกการจัดวางสำหรับการเรนเดอร์
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // แปลงสไลด์แรกของพรีเซนเทชันเป็นอ็อบเจ็กต์ IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // บันทึกรูปภาพในรูปแบบ GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IImage](../../iimage)
* อินเทอร์เฟซ [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* คลาส [Slide](../../slide)
* เนมสเปซ [Aspose.Slides](../../slide)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

คืนค่าอ็อบเจ็กต์ Image ขนาดย่อพร้อมขนาดที่ระบุ.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | IRenderingOptions | ตัวเลือกการเรนเดอร์ |
| imageSize | Size | ขนาดของรูปภาพที่ต้องการสร้าง |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Image.

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| InvalidOperationException | เกิดขึ้นเมื่อ options.SlideLayoutOption เป็น NotesCommentsLayoutingOptions และคุณสมบัติ NotesPosition มีค่า NotesPositions.BottomFull. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IImage](../../iimage)
* อินเทอร์เฟซ [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* คลาส [Slide](../../slide)
* เนมสเปซ [Aspose.Slides](../../slide)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->