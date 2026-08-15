---
title: set_SlideShowType()
second_title: Aspose.Slides C++ API 參考
description: "設定投影片播放類型。由以下 SlideShowType 祖先表示：BrowsedAtKiosk、PresentedBySpeaker 和 BrowsedByIndividual"
type: docs
weight: 14
url: /zh-hant/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) 方法


設定投影片播放類型。由以下 [SlideShowType](../../slideshowtype/) 祖先表示：[BrowsedAtKiosk](../../browsedatkiosk/)、[PresentedBySpeaker](../../presentedbyspeaker/) 和 [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>();

// 設定 "Browsed at a kiosk (full screen)" 類型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// 設定 "Browsed by individual (window)" 類型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// 設定 "Presented by a speaker (full screen)" 類型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [SlideShowType](../../slideshowtype/)
* 類別 [SlideShowSettings](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)