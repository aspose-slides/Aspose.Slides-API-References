---
title: GetAllTextFrames()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนกรอบข้อความทั้งหมดในงานนำเสนอ PPTX.
type: docs
weight: 79
url: /th/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) เมธอด

ส่งคืนทุกกรอบข้อความในงานนำเสนอ PPTX.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | งานนำเสนอที่สแกน |
| withMasters | **bool** | กำหนดว่าควรสแกนสไลด์แม่หรือไม่ |

### ค่ารีเทิร์น

อาเรย์ของอ็อบเจ็กต์ [TextFrame](../../../aspose.slides/textframe/).

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ITextFrame](../../../aspose.slides/itextframe/)
* คลาส [IPresentation](../../../aspose.slides/ipresentation/)
* คลาส [SlideUtil](../)
* เนมสเปซ [Aspose::Slides::Util](../../)
* ไลบรารี [Aspose.Slides](../../../)