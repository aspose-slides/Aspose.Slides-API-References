---
title: get_Arguments()
second_title: Aspose.Slides for C++ API リファレンス
description: 区切り文字で区切られた 1 つ以上の数式要素
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() メソッド

区切り文字で区切られた 1 つ以上の数式要素

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```
## 備考


例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```
## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElementCollection](../../imathelementcollection/)
* クラス [IMathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)