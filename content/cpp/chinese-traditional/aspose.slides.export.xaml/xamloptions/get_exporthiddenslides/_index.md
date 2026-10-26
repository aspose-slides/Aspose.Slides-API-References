---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 參考
description: 判斷是否匯出隱藏的投影片。
type: docs
weight: 1
url: /zh-hant/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() 方法


判斷是否匯出隱藏的投影片。

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## 另見

* 類別 [XamlOptions](../)
* 命名空間 [Aspose::Slides::Export::Xaml](../../)
* 函式庫 [Aspose.Slides](../../../)