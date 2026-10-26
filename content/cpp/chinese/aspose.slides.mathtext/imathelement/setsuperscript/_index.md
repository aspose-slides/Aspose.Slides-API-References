---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API 参考
description: 创建上标
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) 方法

创建上标

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 上标（右侧的上标） |

### 返回值

类型为 [IMathSuperscriptElement](../../imathsuperscriptelement/) 的新数学元素

## 备注



示例: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) 方法

创建上标

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | 上标（右侧的上标） |

### 返回值

类型为 [IMathSuperscriptElement](../../imathsuperscriptelement/) 的新数学元素

## 备注



示例: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathSuperscriptElement](../../imathsuperscriptelement/)
* 类 [IMathElement](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)