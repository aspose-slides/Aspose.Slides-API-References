---
title: MathLeftSubSuperscriptElement()
second_title: Aspose.Slides for C++ API リファレンス
description: MathLeftSubSuperscriptElement クラスの新しいインスタンスを初期化します。
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathleftsubsuperscriptelement/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) コンストラクタ

[MathLeftSubSuperscriptElement](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::Slides::MathText::MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript, System::SharedPtr<IMathElement> superScript)
```

## 備考

例:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathLeftSubSuperscriptElement](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)