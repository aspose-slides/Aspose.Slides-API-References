---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides for C++ API 参考
description: 在右侧创建下标和上标
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

在右侧创建下标和上标

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下标（右侧的下标） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上标（右侧的上标） |

### 返回值

新建类型为 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) 的数学元素

## 备注

示例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) method

在右侧创建下标和上标

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下标（右侧的下标） |
| superscript | [System::String](../../../system/string/) | 上标（右侧的上标） |

### 返回值

新建类型为 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) 的数学元素

## 备注

示例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)