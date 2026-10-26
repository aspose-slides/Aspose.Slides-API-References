---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプのアニメーションオプションを返します。読み取り bool.
type: docs
weight: 27
url: /ja/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() メソッド


シェイプのアニメーションオプションを返します。読み取り **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
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

* クラス [Html5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)