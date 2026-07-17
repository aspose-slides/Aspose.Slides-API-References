---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 参考
description: 获取一个值，指示文本是否在渲染时不使用连字。设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性设置为 false。
type: docs
weight: 105
url: /zh/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() 方法

获取一个值，指示文本是否在渲染时不使用连字。设置为 **true** 时，渲染输出中将禁用连字。默认情况下，此属性设置为 **false**。

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // 在文本渲染中禁用连字

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 另见

* 类 [Html5Options](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)