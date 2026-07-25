---
title: get_AnimateTransitions()
second_title: Aspose.Slides の C++ API リファレンス
description: 遷移アニメーションオプションを返します。読み取り **bool**。
type: docs
weight: 1
url: /ja/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() メソッド

遷移アニメーションオプションを返します。読み取り **bool**。

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
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