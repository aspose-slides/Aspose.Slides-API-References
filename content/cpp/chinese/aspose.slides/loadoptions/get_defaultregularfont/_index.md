---
title: get_DefaultRegularFont()
second_title: Aspose.Slides C++ API 参考
description: "返回在未找到源字体时使用的常规字体。阅读 System::String."
type: docs
weight: 27
url: /zh/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() 方法


返回在未找到源字体时使用的常规字体。阅读 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## 备注


以下示例展示了如何为渲染 PowerPoint [Presentation](../../presentation/) 设置默认字体。 
```cpp
// 使用加载选项定义默认的常规字体和亚洲字体
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// 加载演示文稿
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// 生成幻灯片缩略图
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// 生成 PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// 生成 XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## 另见

* 类 [String](../../../system/string/)
* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)