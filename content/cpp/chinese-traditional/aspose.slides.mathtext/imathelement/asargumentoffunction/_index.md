---
title: AsArgumentOfFunction()
second_title: Aspose.Slides for C++ API 參考
description: 使用此實例作為參數，調用指定的函式
type: docs
weight: 66
url: /zh-hant/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) 方法

使用此實例作為參數，調用指定的函式

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 函式名稱 |

### 傳回值

類型為 [IMathFunction](../../imathfunction/) 的新數學元素

## 備註

範例：
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) 方法

使用此實例作為參數，調用指定的函式

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
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

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) 方法

使用此實例作為參數，調用指定的函式

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | 單參數常用函式類型之一 |

### 傳回值

類型為 [IMathFunction](../../imathfunction/) 的新數學元素

## 備註

範例：
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) 方法

使用此實例作為參數，調用指定的函式並傳入指定的額外參數

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 兩個參數常用函式類型之一：Log、Lim、Min、Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 根據函式類型決定的額外參數 |

### 傳回值

類型為 [IMathFunction](../../imathfunction/) 的新數學元素

## 備註

範例：
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 返回 'x' 以底數 '5' 的對數
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) 方法

使用此實例作為參數，調用指定的函式並傳入指定的額外參數

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 兩個參數常用函式類型之一：Log、Lim、Min、Max |
| additionalArgument | [System::String](../../../system/string/) | 根據函式類型決定的額外參數 |

### 傳回值

類型為 [IMathFunction](../../imathfunction/) 的新數學元素

## 備註

範例：
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 返回 'x' 以底數 '5' 的對數
```

## 參見

* 列舉 [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* 列舉 [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathFunction](../../imathfunction/)
* 類別 [IMathElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)