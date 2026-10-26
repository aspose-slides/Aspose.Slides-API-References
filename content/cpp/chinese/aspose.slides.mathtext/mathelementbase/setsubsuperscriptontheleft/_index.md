---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API 参考
description: 在左侧创建下标和上标
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


在左侧创建下标和上标

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下标（左侧的下标） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上标（左侧的上标） |

### 返回值

新数学元素类型为 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) method


在左侧创建下标和上标

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下标（左侧的下标） |
| superscript | [System::String](../../../system/string/) | 上标（左侧的上标） |

### 返回值

新数学元素类型为 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)