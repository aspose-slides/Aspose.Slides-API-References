---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API 参考
description: 在左侧创建下标和上标
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

在左侧创建下标和上标

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 下标（左侧的下标） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 上标（左侧的上标） |

### 返回值

新数学元素，类型为 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) method

在左侧创建下标和上标

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下标（左侧的下标） |
| superscript | [System::String](../../../system/string/) | 上标（左侧的上标） |

### 返回值

新数学元素，类型为 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)