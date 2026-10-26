---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 参考
description: 设置一个值，以指示文本在渲染时是否不使用连字。设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 false。
type: docs
weight: 118
url: /zh/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) 方法


设置一个值，指示文本是否在渲染时不使用连字。设置为 **true** 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 **false**.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## 备注


示例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // 禁用文本渲染中的连字

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 另请参阅

* 类 [Html5Options](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)