---
title: Function()
second_title: Aspose.Slides for C++ API 参考
description: 使用此实例作为函数名来获取参数的函数
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) 方法


使用此实例作为函数名来获取参数的函数

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 函数的一个参数 |

### 返回值

新数学元素类型为 [IMathFunction](../../imathfunction/)
## 备注



示例：
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) 方法


使用此实例作为函数名来获取参数的函数

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | 函数的一个参数 |

### 返回值

新数学元素类型为 [IMathFunction](../../imathfunction/)
## 备注



示例：
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathFunction](../../imathfunction/)
* 类 [IMathElement](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)