---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides C++ API 参考
description: 在右侧创建下标和上标
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法

在右侧创建下标和上标

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 下标（右侧的下标） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 上标（右侧的上标） |

### 返回值

新数学元素，类型为 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## 备注

示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) 方法

在右侧创建下标和上标

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下标（右侧的下标） |
| superscript | [System::String](../../../system/string/) | 上标（右侧的上标） |

### 返回值

新数学元素，类型为 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## 备注

示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* 类 [IMathElement](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)