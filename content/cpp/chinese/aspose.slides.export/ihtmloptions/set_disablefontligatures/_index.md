---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 参考
description: 设置一个值，指示文本在渲染时是否不使用连字。设置为 true 时，渲染输出中的连字将被禁用。默认情况下，此属性设置为 false。
type: docs
weight: 196
url: /zh/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) 方法


设置一个值，指示文本是否在渲染时不使用连字。设置为 **true** 时，渲染输出中将禁用连字。默认情况下，此属性设置为 **false**。

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## 备注


示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // 禁用文本渲染中的连字

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## 另见

* 类 [IHtmlOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)