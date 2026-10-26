---
title: Shapes()
second_title: Aspose.Slides C++ API 參考
description: 收集 Presentation 中所有 Shape 的實例。
type: docs
weight: 1
url: /zh-hant/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) 方法

收集 [Presentation](../../../aspose.slides/presentation/) 中所有 [Shape](../../../aspose.slides/shape/) 的實例。

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用於收集形狀 |

### 傳回值

在簡報中包含的所有形狀的集合
## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // 如果形狀是 AutoShape，則添加黑色實線邊框
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 類別 [Shape](../../../aspose.slides/shape/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [Collect](../)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)