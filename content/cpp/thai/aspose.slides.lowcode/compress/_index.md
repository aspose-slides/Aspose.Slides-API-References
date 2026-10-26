---
title: Compress
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงถึงกลุ่มของเมธอดที่มีจุดประสงค์เพื่อบีบอัด Presentation.
type: docs
weight: 14
url: /th/aspose.slides.lowcode/compress/
---
## คลาส Compress

แสดงถึงกลุ่มของเมธอดที่มีจุดประสงค์เพื่อบีบอัด [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | ทำการบีบอัดของ [Presentation](../../aspose.slides/presentation/) โดยการลบอักขระที่ไม่ได้ใช้จากฟอนต์ที่ฝังอยู่. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | ทำการบีบอัดของ [Presentation](../../aspose.slides/presentation/) โดยการลบสไลด์เลย์เอาต์ที่ไม่ได้ใช้. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | ทำการบีบอัดของ [Presentation](../../aspose.slides/presentation/) โดยการลบมาสเตอร์สไลด์ที่ไม่ได้ใช้. |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::LowCode](../)
* ไลบรารี [Aspose.Slides](../../)