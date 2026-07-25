---
title: set_AlignScripts()
second_title: Aspose.Slides for C++ API リファレンス
description: 下付き文字/上付き文字の配置を指定します。true の場合、下付き文字と上付き文字は互いに水平に揃えられます。false の場合、ベースの形状に合わせて字間が調整されます。デフォルト値は false です。
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) メソッド

ベース文字の下付き文字/上付き文字の配置を指定します。true の場合、下付き文字と上付き文字は互いに水平に揃えられます。false の場合、ベースの形状に合わせて字間が調整されます。デフォルト値は false です。

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## 備考

例：
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