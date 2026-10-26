---
title: RemoveUnusedMasterSlides()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ทำการบีบอัดของ Presentation โดยการลบสไลด์แม่ที่ไม่ได้ใช้
type: docs
weight: 1
url: /th/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) เมธอด


ทำการบีบอัดของ [Presentation](../../../aspose.slides/presentation/) โดยการลบสไลด์แม่ที่ไม่ได้ใช้

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | อินสแตนซ์ของการนำเสนอ |
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* ประเภทกำหนด [SharedPtr](../../../system/sharedptr/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [Compress](../)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)