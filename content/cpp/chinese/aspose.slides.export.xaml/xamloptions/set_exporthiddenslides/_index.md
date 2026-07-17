---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 参考
description: 确定是否导出隐藏的幻灯片。
type: docs
weight: 14
url: /zh/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) 方法


确定是否导出隐藏的幻灯片。

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## 另见

* 类 [XamlOptions](../)
* 命名空间 [Aspose::Slides::Export::Xaml](../../)
* 库 [Aspose.Slides](../../../)