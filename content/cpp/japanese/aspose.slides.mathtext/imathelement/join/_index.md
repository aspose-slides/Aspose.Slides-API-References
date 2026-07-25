---
title: Join()
second_title: Aspose.Slides for C++ API リファレンス
description: 数学要素を結合し、数学ブロックを形成します
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) メソッド

数学要素を結合し、数学ブロックを形成します

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 結合される要素 |

### 戻り値

このインスタンスと指定された引数を含む新しい [IMathBlock](../../imathblock/)

## 備考



例:  
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) メソッド

数学テキストを結合し、数学ブロックを形成します

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 結合される数学テキスト |

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
* クラス [IMathElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)