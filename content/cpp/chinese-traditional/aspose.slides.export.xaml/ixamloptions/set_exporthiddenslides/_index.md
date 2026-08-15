---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 參考
description: 判斷是否匯出隱藏的投影片。
type: docs
weight: 14
url: /zh-hant/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) 方法


判斷是否匯出隱藏的投影片。

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## 參見

* 類別 [IXamlOptions](../)
* 命名空間 [Aspose::Slides::Export::Xaml](../../)
* 函式庫 [Aspose.Slides](../../../)