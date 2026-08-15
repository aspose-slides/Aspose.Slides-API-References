---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 參考文件
description: 確定是否會匯出隱藏的投影片。
type: docs
weight: 1
url: /zh-hant/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() 方法


確定是否會匯出隱藏的投影片。

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## 另請參閱

* 類別 [IXamlOptions](../)
* 命名空間 [Aspose::Slides::Export::Xaml](../../)
* 函式庫 [Aspose.Slides](../../../)