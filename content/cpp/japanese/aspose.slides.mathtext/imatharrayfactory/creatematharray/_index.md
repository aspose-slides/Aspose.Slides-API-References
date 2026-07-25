---
title: CreateMathArray()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式配列を作成し、指定された要素をその配列に配置します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imatharrayfactory/creatematharray/
---
## IMathArrayFactory::CreateMathArray(System::SharedPtr\<IMathElement\>) メソッド


数式配列を作成し、指定された要素を配列に配置します

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathArrayFactory::CreateMathArray(System::SharedPtr<IMathElement> element)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 配列に配置する数式要素 |

### 戻り値

新しい数式配列

## IMathArrayFactory::CreateMathArray(System::SharedPtr\<IMathElementCollection\>) メソッド


数式配列を作成し、指定された要素を配列に配置します

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathArrayFactory::CreateMathArray(System::SharedPtr<IMathElementCollection> elements)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 配列に配置する数式要素 |

### 戻り値

新しい数式配列

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathArray](../../imatharray/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathArrayFactory](../)
* クラス [IMathElementCollection](../../imathelementcollection/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)