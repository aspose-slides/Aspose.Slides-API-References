---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides C++ API 参考
description: 确定是否导出隐藏的幻灯片。
type: docs
weight: 1
url: /zh/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() 方法


确定是否导出隐藏的幻灯片。

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## 另请参见

* 类 [XamlOptions](../)
* 命名空间 [Aspose::Slides::Export::Xaml](../../)
* 库 [Aspose.Slides](../../../)