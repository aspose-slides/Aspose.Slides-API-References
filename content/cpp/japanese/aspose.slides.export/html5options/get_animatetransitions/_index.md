---
title: get_AnimateTransitions()
second_title: Aspose.Slides for C++ API リファレンス
description: トランジション アニメーション オプションを返します。読み取り bool.
type: docs
weight: 1
url: /ja/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() メソッド

トランジション アニメーション オプションを返します。読み取り **bool**。

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## 備考

例: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## 参照

* クラス [Html5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)