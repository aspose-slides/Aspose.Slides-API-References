---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ลบพื้นที่ที่ถูกตัดของการเติมรูปภาพ.
type: docs
weight: 430
url: /th/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() เมธอด

ลบพื้นที่ที่ถูกตัดของการเติม [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### ค่าที่ส่งคืน

ภาพที่ถูกตัดหรือภาพต้นฉบับหากไม่จำเป็นต้องตัด.

## หมายเหตุ

เมธอดนี้จะแปลงไฟล์เมต้าไฟล์ WMF/EMF เป็นภาพ PNG แบบแรสเตอร์พร้อมกับการตัด.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับ PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// ลบพื้นที่ที่ถูกตัดของรูปภาพใน PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPPImage](../../ippimage/)
* คลาส [PictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)