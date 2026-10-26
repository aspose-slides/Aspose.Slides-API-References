---
title: get_Images()
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: คืนค่าชุดของรูปภาพทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว IImageCollection.
type: docs
weight: 209
url: /th/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() เมธอด

คืนค่าชุดของรูปภาพทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปภาพเป็น BLOB ใน PowerPoint [Presentation](../).
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// สร้างงานนำเสนอใหม่ที่ภาพจะถูกเพิ่มเข้าไป.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// เพิ่มภาพลงในงานนำเสนอ - เราเลือกพฤติกรรม KeepLocked เพราะเราต้องการ
// ไม่ได้ตั้งใจเข้าถึงไฟล์ "largeImage.png" file.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// บันทึกงานนำเสนอ. ขณะสร้างงานนำเสนอขนาดใหญ่ การใช้หน่วยความจำ
// คงอยู่ในระดับต่ำตลอดอายุการใช้งานของอ็อบเจกต์ pres.
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
ตัวอย่างต่อไปนี้เพิ่มไฮเปอร์ลิงก์ให้กับรูปภาพใน PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// เพิ่มภาพลงในงานนำเสนอ
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// สร้างกรอบรูปบนสไลด์ที่ 1 โดยอ้างอิงจากภาพที่เพิ่มไว้ก่อนหน้า
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImageCollection](../../iimagecollection/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)