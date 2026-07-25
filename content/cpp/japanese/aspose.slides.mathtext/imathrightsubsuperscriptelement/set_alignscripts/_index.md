---
title: set_AlignScripts()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された下付き文字/上付き文字の配置です。true の場合、下付き文字と上付き文字は互いに水平に配置されます。false の場合、基底文字の形状に合わせてカーニングされます。デフォルト値は false です。
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) メソッド


下付き文字/上付き文字の配置を指定します。true の場合、下付き文字と上付き文字は互いに水平に配置されます。false の場合、基底文字の形状に合わせてカーニングされます。デフォルト値は false です。

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
```

## 備考


例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## 参照

* クラス [IMathRightSubSuperscriptElement](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)