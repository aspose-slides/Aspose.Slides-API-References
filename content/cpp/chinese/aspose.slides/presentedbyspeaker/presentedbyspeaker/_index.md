---
title: PresentedBySpeaker()
second_title: Aspose.Slides for C++ API 参考
description: 初始化 PresentedBySpeaker 类的一个新实例。
type: docs
weight: 1
url: /zh/aspose.slides/presentedbyspeaker/presentedbyspeaker/
---
## PresentedBySpeaker::PresentedBySpeaker() 构造函数


初始化 [PresentedBySpeaker](../) 类的一个新实例。

```cpp
Aspose::Slides::PresentedBySpeaker::PresentedBySpeaker()
```

## 备注


```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
pres->Save(u"pres.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```




## 另请参阅

* 类 [PresentedBySpeaker](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)