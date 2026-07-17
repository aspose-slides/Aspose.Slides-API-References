---
title: AsArgumentOfFunction()
second_title: Aspose.Slides C++ API 参考
description: 使用此实例作为参数调用指定的函数
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) 方法


使用此实例作为参数调用指定的函数

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 函数名称 |

### 返回值

类型为 [IMathFunction](../../imathfunction/) 的新数学元素
## 备注



示例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) 方法


使用此实例作为参数调用指定的函数

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | 函数名称 |

### 返回值

类型为 [IMathFunction](../../imathfunction/) 的新数学元素
## 备注



示例： 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) 方法


使用此实例作为参数调用指定的函数

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | 单参数常用函数类型之一 |

### 返回值

类型为 [IMathFunction](../../imathfunction/) 的新数学元素
## 备注



示例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) 方法


使用此实例作为参数并使用指定的附加参数调用指定的函数

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 双参数常用函数类型之一：Log、Lim、Min、Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 根据函数类型的附加参数 |

### 返回值

类型为 [IMathFunction](../../imathfunction/) 的新数学元素
## 备注



示例： 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 返回 'x' 的以 5 为底的对数
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) 方法


使用此实例作为参数并使用指定的附加参数调用指定的函数

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 双参数常用函数类型之一：Log、Lim、Min、Max |
| additionalArgument | [System::String](../../../system/string/) | 根据函数类型的附加参数 |

### 返回值

类型为 [IMathFunction](../../imathfunction/) 的新数学元素
## 备注



示例： 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 返回 'x' 的以 5 为底的对数
```

## 另见

* 枚举 [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* 枚举 [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathFunction](../../imathfunction/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)