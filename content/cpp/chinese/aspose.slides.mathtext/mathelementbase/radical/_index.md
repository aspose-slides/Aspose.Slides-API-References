---
title: Radical()
second_title: Aspose.Slides C++ API 参考
description: 指定给定次数的数学根，来自指定的参数。
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) 方法

指定给定次数的数学根，来自指定的参数。

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Radical 的参数 |

### 返回值

类型 [IMathRadical](../../imathradical/) 的新实例

## 备注



示例： ```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) 方法

指定给定次数的数学根，来自指定的参数。

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Radical 的参数 |

### 返回值

类型 [IMathRadical](../../imathradical/) 的新实例

## 备注



示例： ```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathRadical](../../imathradical/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)