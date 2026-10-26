---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API 参考
description: 创建上标
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) 方法

创建上标

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上标（右侧的上标） |

### 返回值

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 备注



示例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) 方法

创建上标

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | 上标（右侧的上标） |

### 返回值

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 备注



示例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathSuperscriptElement](../../imathsuperscriptelement/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)