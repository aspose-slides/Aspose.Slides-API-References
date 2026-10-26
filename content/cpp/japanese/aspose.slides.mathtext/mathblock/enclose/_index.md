---
title: Enclose()
second_title: Aspose.Slides for C++ API リファレンス
description: このブロックの子要素を、括弧などの指定した文字で囲んでフレーム化します
type: docs
weight: 222
url: /ja/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) メソッド

このブロックの子要素を、括弧などの指定した文字で囲んでフレーム化します

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 開始文字（通常は左括弧） |
| endingCharacter | char16_t | 終了文字（通常は右括弧） |

### 戻り値

[IMathDelimiter](../../imathdelimiter/) 型の数式要素で、指定した文字がフレームとして含まれます
## 備考

例:
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) メソッド

このブロックの子要素を、括弧などの指定した文字で囲み、区切り文字で区切ります

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 開始文字（通常は左括弧） |
| endingCharacter | char16_t | 終了文字（通常は右括弧） |
| separatorCharacter | char16_t | 区切り文字 |

### 戻り値

[IMathDelimiter](../../imathdelimiter/) 型の数式要素で、指定した文字がフレームおよび区切り文字として含まれます
## 備考

例:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathDelimiter](../../imathdelimiter/)
* クラス [MathBlock](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)