---
title: set_AnimateShapes()
second_title: Aspose.Slides for C++ APIリファレンス
description: シェイプのアニメーションオプションを設定します。bool を指定します。
type: docs
weight: 40
url: /ja/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) メソッド


シェイプのアニメーションオプションを設定します。**bool** を指定します。

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
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