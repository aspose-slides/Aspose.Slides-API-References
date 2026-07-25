---
title: Group()
second_title: Aspose.Slides for C++ API リファレンス
description: 下カーブ括弧を使用してこの要素をグループに配置します
type: docs
weight: 235
url: /ja/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() メソッド

この要素を、下カーブ括弧を使用してグループに配置します

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### 戻り値

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)

## 備考



例: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) メソッド

この要素を、下カーブ括弧などのグルーピング文字を使用してグループに配置します

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| character | char16_t | 下カーブ括弧 (U+23DF) などのグルーピング文字またはその他 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | グルーピング文字の位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | グループ文字の垂直配置。オブジェクトのベースラインに対する配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification が Top のときはオブジェクトの上端がベースライン上に位置することを意味します。VerticalJustification が Bottom に設定されている場合、オブジェクトの下端がベースライン上に位置します |

### 戻り値

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)

## 備考



例: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## 関連項目

* 列挙体 [MathTopBotPositions](../../mathtopbotpositions/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathGroupingCharacter](../../imathgroupingcharacter/)
* クラス [MathElementBase](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)