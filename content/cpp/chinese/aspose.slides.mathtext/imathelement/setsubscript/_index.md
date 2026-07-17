---
title: SetSubscript()
second_title: Aspose.Slides C++ API 参考
description: 创建下标
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) method


创建下标

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 下标（右侧的下标） |

### 返回值

新数学元素，类型为 [IMathSubscriptElement](../../imathsubscriptelement/)
## 备注



示例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) method


创建下标

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
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

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathSubscriptElement](../../imathsubscriptelement/)
* 类 [IMathElement](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)