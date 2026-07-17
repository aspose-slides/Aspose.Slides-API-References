---
title: set_DefaultRegularFont()
second_title: Aspose.Slides for C++ API 参考
description: "在未找到源字体时使用的常规字体。写入 System::String."
type: docs
weight: 40
url: /zh/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) 方法

设置在未找到源字体时使用的常规字体。写入 [System::String](../../../system/string/)。

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## 备注

以下示例展示了如何为渲染 PowerPoint [Presentation](../../presentation/) 设置默认字体。 
```cpp
// 使用加载选项来定义默认的常规和亚洲字体
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Load the presentation
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Generate slide thumbnail
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Generate PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Generate XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## 另见

* 类 [String](../../../system/string/)
* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)