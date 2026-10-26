---
title: AsArgumentOfFunction()
second_title: Aspose.Slides for C++ API リファレンス
description: このインスタンスを引数として指定された関数を使用します
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) メソッド


このインスタンスを引数として指定された関数を使用します

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 関数名 |

### 戻り値

タイプ [IMathFunction](../../imathfunction/) の新しい数式要素
## 備考



例: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) メソッド


このインスタンスを引数として指定された関数を使用します

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### 引数

| パラメータ | 型 | 説明 |
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

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) メソッド


このインスタンスを引数として指定された関数を使用します

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | 1つの引数を持つ一般的な関数タイプのいずれか |

### 戻り値

タイプ [IMathFunction](../../imathfunction/) の新しい数式要素
## 備考



例: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) メソッド


このインスタンスを引数として指定された関数を使用し、指定された追加引数を使用します

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 2つの引数を持つ一般的な関数タイプのいずれか: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 関数のタイプに応じた追加の引数 |

### 戻り値

タイプ [IMathFunction](../../imathfunction/) の新しい数式要素
## 備考



例: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 'x' の対数（底 '5'）を返します
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) メソッド


このインスタンスを引数として指定された関数を使用し、指定された追加引数を使用します

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 2つの引数を持つ一般的な関数タイプのいずれか: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | 関数のタイプに応じた追加の引数 |

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
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)