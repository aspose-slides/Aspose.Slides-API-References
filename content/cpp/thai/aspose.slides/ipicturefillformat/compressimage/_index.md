---
title: CompressImage()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ และอาจลบพื้นที่ที่ถูกครอบออกด้วย
type: docs
weight: 443
url: /th/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) เมธอด


บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ โดยอาจลบพื้นที่ที่ถูกครอปออกด้วย

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | หากเป็น true เมธอดจะลบพื้นที่ที่ถูกครอปของภาพ ซึ่งอาจทำให้ขนาดลดลงเพิ่มเติม |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | ความละเอียดเป้าหมายสำหรับการบีบอัด ระบุเป็นค่าของเอนัม [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) |

### Return Value

A **bool** indicating whether the image was successfully compressed. Returns ****true****

## Remarks

เมธอดนี้เปลี่ยนขนาดและความละเอียดของภาพเช่นเดียวกับฟีเจอร์ "Picture Format -> Compress Pictures" ของ PowerPoint.

if the image was resized or cropped, otherwise ****false****

. 


ตัวอย่างต่อไปนี้แสดงวิธีใช้เมธอด **CompressImage** เพื่อลดขนาดของภาพในงานนำเสนอโดยตั้งค่าความละเอียดเป้าหมายและลบพื้นที่ที่ถูกครอปออก: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// บีบอัดภาพด้วยความละเอียดเป้าหมาย 150 DPI (ความละเอียดเว็บ) และลบพื้นที่ที่ถูกครอบออก
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) เมธอด


บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ โดยอาจลบพื้นที่ที่ถูกครอปออกด้วย

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | หากเป็น true เมธอดจะลบพื้นที่ที่ถูกครอปของภาพ ซึ่งอาจทำให้ขนาดลดลงเพิ่มเติม |
| resolution | **float** | ความละเอียดเป้าหมายเป็น DPI ค่าต้องเป็นบวกและกำหนดวิธีการปรับขนาดภาพ |

### Return Value

A **bool** indicating whether the image was successfully compressed. Returns ****true****

## Remarks

เมธอดนี้เปลี่ยนขนาดและความละเอียดของภาพเช่นเดียวกับฟีเจอร์ "Picture Format -> Compress Pictures" ของ PowerPoint.

if the image was resized or cropped, otherwise ****false****

. 


ตัวอย่างต่อไปนี้แสดงวิธีใช้เมธอด **CompressImage** เพื่อลดขนาดของภาพในงานนำเสนอโดยตั้งค่าความละเอียดเป้าหมายและลบพื้นที่ที่ถูกครอปออก: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// ดึง PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// บีบอัดภาพด้วยความละเอียดเป้าหมาย 150 DPI (ความละเอียดเว็บ) และลบพื้นที่ที่ถูกครอบออก
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // ความละเอียดเว็บ
```

## ดูเพิ่มเติม

* เอนัม [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* คลาส [IPictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)