---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ APIリファレンス
description: 非表示スライドがエクスポートされるかどうかを決定します。
type: docs
weight: 1
url: /ja/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() メソッド

非表示スライドがエクスポートされるかどうかを決定します。

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## 参照

* クラス [IXamlOptions](../)
* 名前空間 [Aspose::Slides::Export::Xaml](../../)
* ライブラリ [Aspose.Slides](../../../)