---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ลบพื้นที่ที่ถูกตัดของการเติมรูปภาพ.
type: docs
weight: 430
url: /th/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() เมธอด

ลบพื้นที่ที่ถูกตัดของการเติม [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### ค่าที่ส่งคืน

ภาพที่ถูกตัดหรือภาพต้นฉบับหากไม่จำเป็นต้องตัด.

## หมายเหตุ

เมธอดนี้แปลงไฟล์เมตาไฟล์ WMF/EMF ให้เป็นภาพ PNG แบบแรสเตอร์ในขณะตัด.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// รับ PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// ลบพื้นที่ที่ถูกตัดของรูปภาพ PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPPImage](../../ippimage/)
* คลาส [IPictureFillFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)