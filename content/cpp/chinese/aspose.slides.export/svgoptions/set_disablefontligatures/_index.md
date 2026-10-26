---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 参考
description: 设置一个值，指示文本在渲染时是否不使用连字。设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性设置为 false。
type: docs
weight: 339
url: /zh/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) 方法

设置一个值，指示文本是否在渲染时不使用连字。设置为 **true** 时，渲染输出中将禁用连字。默认情况下，此属性设置为 **false**。

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // 在文本渲染中禁用连字

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## 另见

* 类 [SVGOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)