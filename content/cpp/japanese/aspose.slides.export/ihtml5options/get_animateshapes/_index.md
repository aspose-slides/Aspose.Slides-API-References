---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプのアニメーションオプションを返します。bool を読み取ります。
type: docs
weight: 27
url: /ja/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() メソッド

シェイプのアニメーションオプションを返します。**bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## 備考

例: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```

## 参照

* クラス [IHtml5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)