---
title: get_SlideShowType()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ดึงประเภทการแสดงสไลด์ แสดงโดยบรรพบุรุษ SlideShowType ต่อไปนี้: BrowsedAtKiosk, PresentedBySpeaker และ BrowsedByIndividual"
type: docs
weight: 1
url: /th/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() เมธอด

ดึงประเภทการแสดงสไลด์ แสดงโดยบรรพบุรุษ [SlideShowType](../../slideshowtype/) ต่อไปนี้: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) และ [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>();

// ตั้งค่าเป็นประเภท "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// ตั้งค่าเป็นประเภท "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// ตั้งค่าเป็นประเภท "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [SlideShowType](../../slideshowtype/)
* คลาส [SlideShowSettings](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)