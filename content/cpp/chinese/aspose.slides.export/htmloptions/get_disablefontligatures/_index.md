---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 参考
description: 获取一个值，指示文本在渲染时是否不使用连字。设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性设置为 false。
type: docs
weight: 92
url: /zh/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() 方法


获取一个值，指示文本在渲染时是否不使用连字。设置为 **true** 时，渲染输出中将禁用连字。默认情况下，此属性设置为 **false**。

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## 备注


示例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // 在文本渲染中禁用连字

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## 另见

* 类 [HtmlOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)