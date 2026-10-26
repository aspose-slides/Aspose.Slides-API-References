---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API リファレンス
description: 非表示スライドがエクスポートされるかどうかを決定します。デフォルト値は false です。
type: docs
weight: 27
url: /ja/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() メソッド


Determines whether hidden slides will be exported. The default value is false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## 参考

* クラス [IGifOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)