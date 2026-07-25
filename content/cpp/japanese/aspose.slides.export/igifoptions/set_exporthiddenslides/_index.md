---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API リファレンス
description: 非表示スライドがエクスポートされるかどうかを決定します。デフォルト値は false です。
type: docs
weight: 40
url: /ja/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) メソッド


非表示スライドがエクスポートされるかどうかを決定します。デフォルト値は false です。

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```


## 参照

* クラス [IGifOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)