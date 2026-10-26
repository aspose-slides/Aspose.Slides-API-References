---
title: set_AnimateShapes()
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプのアニメーションオプションを設定します。bool を書き込みます。
type: docs
weight: 40
url: /ja/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) メソッド

シェイプのアニメーションオプションを設定します。**bool** を書き込みます。

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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