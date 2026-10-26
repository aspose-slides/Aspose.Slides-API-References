---
title: Shapes()
second_title: Aspose.Slides for C++ API 参考
description: 收集 Presentation 中的所有 Shape 实例。
type: docs
weight: 1
url: /zh/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) 方法

收集 [Presentation](../../../aspose.slides/presentation/) 中的所有 [Shape](../../../aspose.slides/shape/) 实例。

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于收集形状 |

### 返回值

演示文稿中包含的所有形状的集合

## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // 如果形状是 AutoShape，则添加黑色实线边框
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

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [Shape](../../../aspose.slides/shape/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [Collect](../)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)