---
title: AsArgumentOfFunction()
second_title: Aspose.Slides for C++ API 參考
description: 使用此實例作為參數，取得指定的函式
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) 方法

使用此實例作為參數，取得指定的函式

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 函式名稱 |

### 傳回值

類型為 [IMathFunction](../../imathfunction/) 的新數學元素

## 備註



範例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) 方法

使用此實例作為參數，取得指定的函式

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | 函式名稱 |

### 傳回值

類型為 [IMathFunction](../../imathfunction/) 的新數學元素

## 備註



範例： 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) 方法

使用此實例作為參數，取得指定的函式

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | 單一參數的常見函式類型之一 |

### 傳回值

類型為 [IMathFunction](../../imathfunction/) 的新數學元素

## 備註



範例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) 方法

使用此實例作為參數，取得指定的函式並附加其他參數

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 兩個參數的常見函式類型之一：Log、Lim、Min、Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 依函式類型而定的額外參數 |

### 傳回值

類型為 [IMathFunction](../../imathfunction/) 的新數學元素

## 備註



範例： 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 回傳 'x' 以底數 '5' 的對數
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) 方法

使用此實例作為參數，取得指定的函式並附加其他參數

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 兩個參數的常見函式類型之一：Log、Lim、Min、Max |
| additionalArgument | [System::String](../../../system/string/) | 依函式類型而定的額外參數 |

### 傳回值

類型為 [IMathFunction](../../imathfunction/) 的新數學元素

## 備註



範例： 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 回傳 'x' 以底數 '5' 的對數
```

## 參閱

* 列舉 [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* 列舉 [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathFunction](../../imathfunction/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathElementBase](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)