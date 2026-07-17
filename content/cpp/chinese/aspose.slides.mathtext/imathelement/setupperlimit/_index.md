---
title: SetUpperLimit()
second_title: Aspose.Slides for C++ API 参考
description: 接受上限
type: docs
weight: 144
url: /zh/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) 方法

接受上限

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### 返回值

新实例类型 [IMathLimit](../../imathlimit/)
## 备注

示例：
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) 方法

接受上限

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### 返回值

新实例类型 [IMathLimit](../../imathlimit/)
## 备注

示例：
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathLimit](../../imathlimit/)
* 类 [IMathElement](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)