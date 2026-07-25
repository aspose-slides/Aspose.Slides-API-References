---
title: Delimit()
second_title: Aspose.Slides for C++ API リファレンス
description: 区切り文字で子要素すべてを区切ります（角括弧なし）。
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) メソッド

Delimits all child elements with separator character (without the brackets)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| separatorCharacter | char16_t | 区切り文字として使用される文字 |

### 戻り値

[IMathDelimiter](../../imathdelimiter/) 要素のインスタンス

## 備考



例: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)