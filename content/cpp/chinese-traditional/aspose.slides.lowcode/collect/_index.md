---
title: Collect
second_title: Aspose.Slides for C++ API 參考
description: 表示一組旨在從 Presentation 收集不同類型模型物件的方法。
type: docs
weight: 1
url: /zh-hant/aspose.slides.lowcode/collect/
---
## Collect 類別

表示一組旨在從 [Presentation](../../aspose.slides/presentation/) 收集不同類型模型物件的方法。

```cpp
class Collect
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 收集 [Presentation](../../aspose.slides/presentation/) 中所有 [Shape](../../aspose.slides/shape/) 的實例。 |
## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... 更改形狀格式或其他屬性
}
```

## 參見

* 命名空間 [Aspose::Slides::LowCode](../)
* 程式庫 [Aspose.Slides](../../)