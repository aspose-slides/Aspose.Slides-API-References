---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 参考
description: 获取一个值，指示文本在渲染时是否不使用连字。设置为 true 时，渲染输出中的连字将被禁用。默认情况下，此属性设置为 false。
type: docs
weight: 40
url: /zh/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() 方法

获取一个值，指示文本是否在渲染时不使用连字。设置为 **true** 时，渲染输出中的连字将被禁用。默认情况下，此属性设置为 **false**。

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // 禁用文本渲染中的连字

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## 另请参见

* 类 [RenderingOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)