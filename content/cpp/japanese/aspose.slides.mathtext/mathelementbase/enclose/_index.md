---
title: Enclose()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式要素を括弧で囲みます
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() メソッド

数式要素を括弧で囲みます

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```

### 戻り値

括弧を含む [IMathDelimiter](../../imathdelimiter/) 型の数式要素

## 備考



例: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) メソッド

数式要素を括弧やその他の文字で枠付けして囲みます

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 開始文字 (通常は左括弧) |
| endingCharacter | char16_t | 終了文字 (通常は右括弧) |

### 戻り値

指定された文字で枠付けされた [IMathDelimiter](../../imathdelimiter/) 型の数式要素

## 備考



例: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathDelimiter](../../imathdelimiter/)
* クラス [MathElementBase](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)