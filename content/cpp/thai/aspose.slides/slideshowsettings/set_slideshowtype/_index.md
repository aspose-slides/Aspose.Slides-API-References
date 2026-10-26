---
title: set_SlideShowType()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "กำหนดประเภทการแสดงสไลด์ แสดงโดยบรรพบุรุษ SlideShowType ดังต่อไปนี้: BrowsedAtKiosk, PresentedBySpeaker และ BrowsedByIndividual"
type: docs
weight: 14
url: /th/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) เมธอด

กำหนดประเภทการแสดงสไลด์. แสดงโดยบรรพบุรุษ [SlideShowType](../../slideshowtype/) ต่อไปนี้: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) และ [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>();

// เพื่อกำหนดประเภท "Browsed at a kiosk (full screen)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// เพื่อกำหนดประเภท "Browsed by individual (window)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// เพื่อกำหนดประเภท "Presented by a speaker (full screen)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [SlideShowType](../../slideshowtype/)
* คลาส [SlideShowSettings](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)