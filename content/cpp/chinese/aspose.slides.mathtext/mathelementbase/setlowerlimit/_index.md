---
title: SetLowerLimit()
second_title: Aspose.Slides C++ API 参考
description: 接受下限
type: docs
weight: 144
url: /zh/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) 方法


接受下限

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### 返回值

类型为 [IMathLimit](../../imathlimit/) 的新实例
## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) 方法


接受下限

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### 返回值

类型为 [IMathLimit](../../imathlimit/) 的新实例
## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathLimit](../../imathlimit/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)