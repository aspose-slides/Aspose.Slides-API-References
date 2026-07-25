---
title: CreateMathFunction()
second_title: Aspose.Slides for C++ API リファレンス
description: 数学関数を作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド

数学関数を作成します

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 関数名として使用される要素 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 関数の引数として使用される要素 |

### 戻り値

新しい数学関数

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) メソッド

数学関数を作成します

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | 関数名 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 関数の引数として使用される要素 |

### 戻り値

新しい数学関数

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathFunction](../../imathfunction/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathFunctionFactory](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)