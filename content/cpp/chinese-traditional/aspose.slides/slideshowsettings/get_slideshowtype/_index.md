---
title: get_SlideShowType()
second_title: Aspose.Slides C++ API 參考文件
description: "取得投影片放映類型。由以下 SlideShowType 祖先表示：BrowsedAtKiosk、PresentedBySpeaker 和 BrowsedByIndividual"
type: docs
weight: 1
url: /zh-hant/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() 方法


取得投影片放映類型。由以下 [SlideShowType](../../slideshowtype/) 祖先表示：[BrowsedAtKiosk](../../browsedatkiosk/)、[PresentedBySpeaker](../../presentedbyspeaker/) 和 [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>();

// 設定「在資訊站點瀏覽（全螢幕）」類型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// 設定「個別瀏覽（視窗）」類型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// 設定「由講者呈現（全螢幕）」類型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [SlideShowType](../../slideshowtype/)
* 類別 [SlideShowSettings](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)