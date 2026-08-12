---
title: WriteAsEmf()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: บันทึกภาพ SVG เป็นไฟล์ EMF.
type: docs
weight: 53
url: /th/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) เมธอด

บันทึกภาพ SVG เป็นไฟล์ EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมเป้าหมาย |
## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีบันทึกภาพ SVG ไปยังเมทาไฟล์. 
```cpp
// สร้างภาพ SVG ใหม่
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// บันทึกภาพ SVG เป็นเมทาไฟล์
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 ตัวอย่างนี้แสดงวิธีเพิ่มภาพ SVG เป็นเมทาไฟล์ไปยังคอลเลกชันภาพการนำเสนอ. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// สร้างภาพ SVG ใหม่
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// บันทึกภาพ SVG เป็นเมทาไฟล์
svgImage->WriteAsEmf(memStream);
// เพิ่มเมทาไฟล์ไปยังคอลเลกชันภาพ
pres->get_Images()->AddImage(memStream->ToArray());
```

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [ISvgImage](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)