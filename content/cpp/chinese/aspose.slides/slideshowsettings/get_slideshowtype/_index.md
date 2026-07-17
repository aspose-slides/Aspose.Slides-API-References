---
title: get_SlideShowType()
second_title: Aspose.Slides C++ API 参考
description: "获取幻灯片放映类型。由以下 SlideShowType 祖先表示：BrowsedAtKiosk、PresentedBySpeaker 和 BrowsedByIndividual"
type: docs
weight: 1
url: /zh/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() 方法

获取幻灯片放映类型。由以下 [SlideShowType](../../slideshowtype/) 祖先表示：[BrowsedAtKiosk](../../browsedatkiosk/)、[PresentedBySpeaker](../../presentedbyspeaker/) 和 [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## 备注

```cpp
auto pres = System::MakeObject<Presentation>();

// 设置 "Browsed at a kiosk (full screen)" 类型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// 设置 "Browsed by individual (window)" 类型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// 设置 "Presented by a speaker (full screen)" 类型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [SlideShowType](../../slideshowtype/)
* 类 [SlideShowSettings](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)