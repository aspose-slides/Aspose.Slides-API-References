---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式ブロックを作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() メソッド

数式ブロックを作成します

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```

### 戻り値

新しい数式ブロック

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) メソッド

数式ブロックを作成し、要素を配置します

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 数式要素 |

### 戻り値

新しい数式ブロック

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) メソッド

数式ブロックを作成し、要素を配置します

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 数式要素 |

### 戻り値

新しい数式ブロック

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBlock](../../imathblock/)
* クラス [MathBlockFactory](../)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathElementCollection](../../imathelementcollection/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)