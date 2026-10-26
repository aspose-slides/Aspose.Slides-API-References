---
title: CompressImage()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: บีบอัดรูปภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ โดยอาจลบส่วนที่ถูกครอปออกด้วย
type: docs
weight: 443
url: /th/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) เมธอด

บีบอัดรูปภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ โดยอาจจะลบส่วนที่ถูกครอปออกด้วย

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | ถ้าเป็น true เมธอดจะลบส่วนที่ครอปของรูปภาพ ซึ่งอาจทำให้ขนาดลดลงอีก |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | ความละเอียดเป้าหมายสำหรับการบีบอัด ระบุเป็นค่าใน enum [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) |

### ค่าที่คืนกลับ

ค่าบูลีน **bool** ที่บ่งชี้ว่ารูปภาพถูกบีบอัดสำเร็จหรือไม่ ค่าที่คืนคือ ****true****

## หมายเหตุ

เมธอดนี้เปลี่ยนขนาดและความละเอียดของรูปภาพเช่นเดียวกับคุณสมบัติ "Picture Format -> Compress Pictures" ของ PowerPoint

ถ้ารูปภาพถูกปรับขนาดหรือครอป มิฉะนั้น ****false****

. 

ตัวอย่างต่อไปนี้แสดงวิธีการใช้เมธอด **CompressImage** เพื่อลดขนาดรูปภาพในงานนำเสนอโดยตั้งค่าความละเอียดเป้าหมายและลบส่วนที่ครอปออก: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// บีบอัดรูปภาพด้วยความละเอียดเป้าหมาย 150 DPI (ความละเอียดเว็บ) และลบส่วนที่ถูกครอปออก
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) เมธอด

บีบอัดรูปภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ โดยอาจจะลบส่วนที่ถูกครอปออกด้วย

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | ถ้าเป็น true เมธอดจะลบส่วนที่ครอปของรูปภาพ ซึ่งอาจทำให้ขนาดลดลงอีก |
| resolution | **float** | ความละเอียดเป้าหมายใน DPI ค่านี้ต้องเป็นจำนวนบวกและกำหนดวิธีการปรับขนาดของรูปภาพ |

### ค่าที่คืนกลับ

ค่าบูลีน **bool** ที่บ่งชี้ว่ารูปภาพถูกบีบอัดสำเร็จหรือไม่ ค่าที่คืนคือ ****true****

## หมายเหตุ

เมธอดนี้เปลี่ยนขนาดและความละเอียดของรูปภาพเช่นเดียวกับคุณสมบัติ "Picture Format -> Compress Pictures" ของ PowerPoint

ถ้ารูปภาพถูกปรับขนาดหรือครอป มิฉะนั้น ****false****

. 

ตัวอย่างต่อไปนี้แสดงวิธีการใช้เมธอด **CompressImage** เพื่อลดขนาดรูปภาพในงานนำเสนอโดยตั้งค่าความละเอียดเป้าหมายและลบส่วนที่ครอปออก: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// ดึง PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// บีบอัดรูปภาพด้วยความละเอียดเป้าหมาย 150 DPI (ความละเอียดเว็บ) และลบส่วนที่ถูกครอปออก
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // ความละเอียดเว็บ
```

## See Also

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)