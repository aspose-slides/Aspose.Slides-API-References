---
title: get_MasterTheme()
second_title: Aspose.Slides C++ API 参考
description: "返回主主题。只读 Theme::IMasterTheme。"
type: docs
weight: 404
url: /zh/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() 方法

返回主主题。只读 [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/)。

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## 备注

以下示例展示了如何通过更改 PowerPoint [Presentation](../) 的元素部件来更改主题效果。

```cpp
// 实例化一个表示演示文件的 Presentation 对象
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)