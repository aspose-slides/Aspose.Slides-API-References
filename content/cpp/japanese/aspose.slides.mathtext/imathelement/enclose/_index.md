---
title: Enclose()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式要素をかっこで囲みます
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() メソッド


数式要素をかっこで囲みます

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### 戻り値

[IMathDelimiter](../../imathdelimiter/) 型の数式要素で、かっこが含まれます
## 備考



例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) メソッド


この要素をかっこや他の文字など、指定した文字で枠付けして囲みます

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | 開始文字 (通常は左括弧) |
| endingCharacter | char16_t | 終了文字 (通常は右括弧) |

### 戻り値

[IMathDelimiter](../../imathdelimiter/) 型の数式要素で、指定した文字が枠として含まれます
## 備考



例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathDelimiter](../../imathdelimiter/)
* クラス [IMathElement](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)