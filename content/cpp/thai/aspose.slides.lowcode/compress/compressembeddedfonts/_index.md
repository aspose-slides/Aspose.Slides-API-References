---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการบีบอัด Presentation โดยการลบอักขระที่ไม่ได้ใช้จากแบบอักษรที่ฝังไว้
type: docs
weight: 27
url: /th/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) เมธอด


ทำการบีบอัดของ [Presentation](../../../aspose.slides/presentation/) โดยการลบอักขระที่ไม่ได้ใช้จากแบบอักษรที่ฝังไว้.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | อินสแตนซ์ของการนำเสนอ |
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [Compress](../)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)