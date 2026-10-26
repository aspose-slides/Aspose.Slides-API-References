---
title: Join()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: この数式ブロックに数式要素を結合します
type: docs
weight: 183
url: /ja/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) メソッド


この数式ブロックに数式要素を結合します

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 結合する要素 |

### 戻り値

現在の [IMathBlock](../../imathblock/) インスタンス

## 備考



例: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) メソッド


この数式ブロックに数式テキストを結合します

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 結合する数式テキスト |

### 戻り値

このインスタンスと指定された引数を含む新しい [IMathBlock](../../imathblock/)

## 備考



例: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBlock](../../imathblock/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBlock](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)