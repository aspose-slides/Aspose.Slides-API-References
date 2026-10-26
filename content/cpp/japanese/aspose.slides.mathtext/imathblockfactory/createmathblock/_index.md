---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式ブロックを作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() メソッド


数式ブロックを作成します

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```


### 戻り値

新しい数式ブロック

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) メソッド


数式ブロックを作成し、その要素を配置します

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 数式要素 |

### 戻り値

新しい数式ブロック

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) メソッド


数式ブロックを作成し、要素を配置します

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 数式要素 |

### 戻り値

新しい数式ブロック

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBlock](../../imathblock/)
* クラス [IMathBlockFactory](../)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathElementCollection](../../imathelementcollection/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)