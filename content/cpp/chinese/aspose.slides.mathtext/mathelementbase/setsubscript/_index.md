---
title: SetSubscript()
second_title: Aspose.Slides for C++ API 参考
description: 创建下标
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) 方法

创建下标

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下标（右侧的下标） |

### 返回值

新数学元素，类型为 [IMathSubscriptElement](../../imathsubscriptelement/)

## 备注



示例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) 方法

创建下标

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下标（右侧的下标） |

### 返回值

新数学元素，类型为 [IMathSubscriptElement](../../imathsubscriptelement/)

## 备注



示例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathSubscriptElement](../../imathsubscriptelement/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)