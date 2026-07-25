---
title: Accent()
second_title: Aspose.Slides for C++ API リファレンス
description: この要素の上部に付くアクセント記号（文字）を設定します
type: docs
weight: 196
url: /ja/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) メソッド

この要素の上に付くアクセント記号（文字）を設定します

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| accentCharacter | char16_t | アクセント文字。値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります |

### 戻り値

型 [IMathAccent](../../imathaccent/) の新しいインスタンス

## 備考



例: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathAccent](../../imathaccent/)
* クラス [MathElementBase](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)