---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ทำการบีบอัดของ Presentation โดยการลบสไลด์เค้าโครงที่ไม่ได้ใช้
type: docs
weight: 14
url: /th/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) เมธอด

ทำการบีบอัดของ [Presentation](../../../aspose.slides/presentation/) โดยการลบสไลด์เค้าโครงที่ไม่ได้ใช้

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | อินสแตนซ์ของการนำเสนอ |

## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [Compress](../)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)