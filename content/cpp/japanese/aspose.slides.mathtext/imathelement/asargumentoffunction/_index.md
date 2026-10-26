---
title: AsArgumentOfFunction()
second_title: Aspose.Slides for C++ API リファレンス
description: このインスタンスを引数として、指定された関数を使用します
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) メソッド

このインスタンスを引数として、指定された関数を使用します

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 関数名 |

### 戻り値

タイプ [IMathFunction](../../imathfunction/) の新しい数式要素

## 備考



例: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) メソッド

このインスタンスを引数として、指定された関数を使用します

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | 関数名 |

### 戻り値

タイプ [IMathFunction](../../imathfunction/) の新しい数式要素

## 備考



例: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) メソッド

このインスタンスを引数として、指定された関数を使用します

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | 1 引数の一般的な関数タイプのいずれか |

### 戻り値

タイプ [IMathFunction](../../imathfunction/) の新しい数式要素

## 備考



例: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) メソッド

このインスタンスを引数として、指定された関数を使用します

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 2 引数の一般的な関数タイプのいずれか: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 関数のタイプに応じた追加引数 |

### 戻り値

タイプ [IMathFunction](../../imathfunction/) の新しい数式要素

## 備考



例: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 'x' の底 '5' の対数を返します
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) メソッド

このインスタンスを引数として、指定された関数を使用します

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 2 引数の一般的な関数タイプのいずれか: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | 関数のタイプに応じた追加引数 |

### 戻り値

タイプ [IMathFunction](../../imathfunction/) の新しい数式要素

## 備考



例: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 'x' の底 '5' の対数を返します
```

## 参照

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)