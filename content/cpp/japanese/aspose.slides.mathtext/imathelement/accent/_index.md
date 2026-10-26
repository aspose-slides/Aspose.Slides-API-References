---
title: Accent()
second_title: Aspose.Slides for C++ API リファレンス
description: この要素の上部に付くアクセント記号（文字）を設定します
type: docs
weight: 209
url: /ja/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) method

この要素の上部に付くアクセント記号（文字）を設定します

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| accentCharacter | char16_t | アクセント文字。値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります |

### 戻り値

型 [IMathAccent](../../imathaccent/) の新しいインスタンス

## 備考



例: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathAccent](../../imathaccent/)
* クラス [IMathElement](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)