---
title: GetImage()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยการปรับสเกลตามกำหนด.
type: docs
weight: 144
url: /th/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) เมธอด

ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยการปรับสเกลตามกำหนด

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scaleX | **float** | ค่าที่ใช้ในการปรับสเกล Thumbnail นี้ในทิศทางแกน x |
| scaleY | **float** | ค่าที่ใช้ในการปรับสเกล Thumbnail นี้ในทิศทางแกน y |

### ค่าที่ส่งคืน

[IImage](../../iimage/) อ็อบเจ็กต์

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีสร้างภาพย่อจาก PowerPoint [Presentation](../../presentation/):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
ตัวอย่างต่อไปนี้แ 보여การแปลงสไลด์เป็นบิทแมพและบันทึกภาพในรูปแบบ PNG:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// แปลงสไลด์แรกในงานนำเสนอเป็นอ็อบเจ็กต์ Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// บันทึกภาพในรูปแบบ PNG
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint PPT/PPTX เป็น JPG:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // สร้างภาพขนาดเต็มสเกล
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // บันทึกรูปภาพลงดิสก์ในรูปแบบ JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint PPT/PPTX เป็น JPG พร้อมการกำหนดขนาดที่ปรับแต่งเอง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// กำหนดมิติ
int32_t desiredX = 1200;
int32_t desiredY = 800;
// รับค่าที่สเกลของ X และ Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // สร้างภาพขนาดเต็มสเกล
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // บันทึกรูปภาพลงดิสก์ในรูปแบบ JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() เมธอด

ส่งคืนอ็อบเจ็กต์ Thumbnail Image (20% ของขนาดจริง)

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) เมธอด

ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของภาพที่จะสร้าง |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ Image

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีแปลงสไลด์เป็นภาพโดยกำหนดขนาดที่กำหนดเองโดยใช้ C#
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// แปลงสไลด์แรกในงานนำเสนอเป็น Bitmap ด้วยขนาดที่ระบุ
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// บันทึกรูปภาพในรูปแบบ JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) เมธอด

ส่งคืนอ็อบเจ็กต์ Thumbnail tiff image ด้วยพารามิเตอร์ที่ระบุ

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | ตัวเลือก Tiff |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ Image

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) เมธอด

ส่งคืนอ็อบเจ็กต์ Thumbnail Image

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์ |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ Image

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) เมธอด

ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยการปรับสเกลตามกำหนด

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์ |
| scaleX | **float** | ค่าที่ใช้ในการปรับสเกล Thumbnail นี้ในทิศทางแกน x |
| scaleY | **float** | ค่าที่ใช้ในการปรับสเกล Thumbnail นี้ในทิศทางแกน y |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ Bitmap

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีแปลงสไลด์พร้อมบันทึกย่อและความคิดเห็นเป็น [Images](../../images/) โดยใช้ C#
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// สร้างตัวเลือกการเรนเดอร์
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// สร้างตัวเลือกการจัดวางบันทึกและความคิดเห็น
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// กำหนดตำแหน่งของบันทึกบนหน้า
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// กำหนดตำแหน่งของความคิดเห็นบนหน้า
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// กำหนดความกว้างของพื้นที่แสดงผลความคิดเห็น
notesCommentsLayouting->set_CommentsAreaWidth(500);
// กำหนดสีสำหรับพื้นที่ความคิดเห็น
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// ตั้งค่าตัวเลือกการจัดวางสำหรับการเรนเดอร์
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// แปลงสไลด์แรกของงานนำเสนอเป็นอ็อบเจ็กต์ IImage
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// บันทึกภาพในรูปแบบ GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) เมธอด

ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์ |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของภาพที่จะสร้าง |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ Image

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImage](../../iimage/)
* คลาส [Slide](../)
* คลาส [Size](../../../system.drawing/size/)
* คลาส [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* คลาส [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)