---
title: Group()
second_title: Aspose.Slides for C++ API リファレンス
description: この要素を下カールブラケットを使用してグループに配置します
type: docs
weight: 248
url: /ja/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() メソッド


この要素を下カールブラケットを使用してグループに配置します

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### 戻り値

型 [IMathGroupingCharacter](../../imathgroupingcharacter/) の新しいインスタンス
## 備考



例: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) メソッド


この要素を下カールブラケットやその他のグルーピング文字を使用してグループに配置します

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| character | char16_t | BOTTOM CURLY BRACKET (U+23DF) などのグルーピング文字 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | グルーピング文字の位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | グループ文字の垂直方向の配置。オブジェクトのベースラインに対する整列を指定します。たとえば、グループ文字がオブジェクトの上にある場合、Top の VerticalJustification はオブジェクトの上部がベースライン上にあることを意味します。Bottom に設定された場合、オブジェクトの下部がベースライン上にあります |

### 戻り値

型 [IMathGroupingCharacter](../../imathgroupingcharacter/) の新しいインスタンス
## 備考



例: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## 関連項目

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)