---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API リファレンス
description: 非表示スライドをエクスポートするかどうかを決定します。
type: docs
weight: 1
url: /ja/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() メソッド

非表示スライドをエクスポートするかどうかを決定します。

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## 備考


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```


## 参照

* クラス [XamlOptions](../)
* 名前空間 [Aspose::Slides::Export::Xaml](../../)
* ライブラリ [Aspose.Slides](../../../)