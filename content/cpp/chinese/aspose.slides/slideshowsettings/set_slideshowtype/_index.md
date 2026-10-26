---
title: set_SlideShowType()
second_title: Aspose.Slides C++ API 参考
description: "设置幻灯片放映类型。由以下 SlideShowType 祖先表示：BrowsedAtKiosk、PresentedBySpeaker 和 BrowsedByIndividual"
type: docs
weight: 14
url: /zh/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) 方法

设置幻灯片放映类型。由以下 [SlideShowType](../../slideshowtype/) 祖先表示：[BrowsedAtKiosk](../../browsedatkiosk/)、[PresentedBySpeaker](../../presentedbyspeaker/) 和 [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## 备注

```cpp
auto pres = System::MakeObject<Presentation>();

// 设置“在信息亭浏览（全屏）”类型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// 设置“个人浏览（窗口）”类型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// 设置“演讲者呈现（全屏）”类型
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [SlideShowType](../../slideshowtype/)
* 类 [SlideShowSettings](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)