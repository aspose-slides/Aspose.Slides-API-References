---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 參考
description: 判斷是否匯出隱藏的投影片。
type: docs
weight: 14
url: /zh-hant/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) 方法


判斷是否匯出隱藏的投影片。

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
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