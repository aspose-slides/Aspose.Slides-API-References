---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides C++ API 参考
description: 确定是否导出隐藏的幻灯片。
type: docs
weight: 14
url: /zh/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) 方法

确定是否导出隐藏的幻灯片。

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## 参见

* 类 [IXamlOptions](../)
* 命名空间 [Aspose::Slides::Export::Xaml](../../)
* 库 [Aspose.Slides](../../../)