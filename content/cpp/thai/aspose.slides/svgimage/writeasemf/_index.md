---
title: WriteAsEmf()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: บันทึกภาพ SVG เป็นไฟล์ EMF.
type: docs
weight: 66
url: /th/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) เมธอด

บันทึกภาพ SVG เป็นไฟล์ EMF

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมเป้าหมาย |
## หมายเหตุ



ตัวอย่างต่อไปนี้แสดงวิธีบันทึกภาพ SVG ลงในเมตาฟายล์. 
```cpp
// สร้างภาพ SVG ใหม่
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// บันทึกภาพ SVG เป็นเมตาฟายล์
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 ตัวอย่างนี้แสดงวิธีเพิ่มภาพ SVG เป็นเมตาฟายล์ไปยังคอลเลกชันภาพของการนำเสนอ. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// สร้างภาพ SVG ใหม่
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// บันทึกภาพ SVG เป็นเมตาฟายล์
svgImage->WriteAsEmf(memStream);
// เพิ่มเมตาฟายล์ไปยังคอลเลกชันภาพ
pres->get_Images()->AddImage(memStream->ToArray());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [SvgImage](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)