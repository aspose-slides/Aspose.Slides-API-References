---
title: Function()
second_title: Aspose.Slides C++ API 参考
description: 使用此实例作为函数名，获取带参数的函数
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) 方法


使用此实例作为函数名，获取一个带参数的函数

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 函数的参数 |

### 返回值

新数学元素类型 [IMathFunction](../../imathfunction/)
## 备注



示例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) 方法


使用此实例作为函数名，获取一个带参数的函数

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | 函数的参数 |

### 返回值

新数学元素类型 [IMathFunction](../../imathfunction/)
## 备注



示例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathFunction](../../imathfunction/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)