---
title: set_AnimateTransitions()
second_title: Aspose.Slides for C++ API リファレンス
description: 遷移アニメーションオプションを設定します。boolを書き込みます。
type: docs
weight: 14
url: /ja/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) メソッド


遷移アニメーションのオプションを設定します。**bool** を書き込みます。

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
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