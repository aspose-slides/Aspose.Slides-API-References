---
title: get_AlignScripts()
second_title: Aspose.Slides for C++ API リファレンス
description: 下付き文字/上付き文字の配置を指定します。true の場合、下付き文字と上付き文字は水平方向に互いに揃えられます。false の場合、基底文字の形状に合わせてカーニングされます。既定値は false です。
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() メソッド


下付き文字/上付き文字の配置を指定します。true の場合、下付き文字と上付き文字は水平方向に互いに揃えられます。false の場合、基底文字の形状に合わせてカーニングされます。既定値は false です。

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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

* クラス [MathRightSubSuperscriptElement](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)