---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API リファレンス
description: 非表示のスライドがエクスポートされるかどうかを決定します。
type: docs
weight: 14
url: /ja/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) method


非表示のスライドがエクスポートされるかどうかを決定します。

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
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