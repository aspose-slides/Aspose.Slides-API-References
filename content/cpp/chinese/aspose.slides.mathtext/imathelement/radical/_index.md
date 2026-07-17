---
title: Radical()
second_title: Aspose.Slides for C++ API 参考
description: 指定给定次数的数学根，使用指定的参数。
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) 方法

指定给定次数的数学根，使用指定的参数。

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 根的参数 |

### 返回值

新实例类型 [IMathRadical](../../imathradical/)
## 备注



示例：
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) 方法

指定给定次数的数学根，使用指定的参数。

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | 根的参数 |

### 返回值

新实例类型 [IMathRadical](../../imathradical/)
## 备注



示例：
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathRadical](../../imathradical/)
* 类 [IMathElement](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)