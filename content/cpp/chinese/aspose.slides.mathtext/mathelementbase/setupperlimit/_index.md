---
title: SetUpperLimit()
second_title: Aspose.Slides for C++ API 参考
description: 接受上限
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) 方法

接受上限

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### 返回值

[IMathLimit](../../imathlimit/) 类型的新实例

## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) 方法

接受上限

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### 返回值

[IMathLimit](../../imathlimit/) 类型的新实例

## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathLimit](../../imathlimit/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)