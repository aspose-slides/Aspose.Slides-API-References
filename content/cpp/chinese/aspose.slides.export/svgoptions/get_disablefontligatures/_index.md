---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 参考
description: 获取一个值，指示文本在渲染时是否不使用连字。设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 false。
type: docs
weight: 326
url: /zh/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() 方法

获取一个值，指示文本在渲染时是否不使用连字。设置为 **true** 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 **false**。

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
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

## 另请参见

* 类 [SVGOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)