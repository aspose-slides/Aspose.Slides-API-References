---
title: set_AnimateTransitions()
second_title: Aspose.Slides for C++ API リファレンス
description: トランジションのアニメーションオプションを設定します。bool を記述します。
type: docs
weight: 14
url: /ja/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) メソッド


トランジションのアニメーションオプションを設定します。**bool** を記述します。

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
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

* クラス [IHtml5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)