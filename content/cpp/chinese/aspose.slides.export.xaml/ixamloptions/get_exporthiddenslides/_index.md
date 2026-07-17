---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 参考
description: 确定是否导出隐藏的幻灯片。
type: docs
weight: 1
url: /zh/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() 方法


确定是否导出隐藏的幻灯片。

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## 另见

* 类 [IXamlOptions](../)
* 命名空间 [Aspose::Slides::Export::Xaml](../../)
* 库 [Aspose.Slides](../../../)