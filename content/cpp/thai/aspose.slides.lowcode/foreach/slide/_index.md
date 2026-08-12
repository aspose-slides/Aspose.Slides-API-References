---
title: Slide()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "วนซ้ำแต่ละ ForEach::Slide ใน Presentation."
type: docs
weight: 1
url: /th/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) เมธอด

วนซ้ำแต่ละ [ForEach::Slide](./) ใน [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) เพื่อวนซ้ำสไลด์ |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | คอลแบ็กที่ถูกเรียกสำหรับแต่ละสไลด์ |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* ประเภทนิยาม [ForEachSlideCallback](../foreachslidecallback/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [ForEach](../)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)