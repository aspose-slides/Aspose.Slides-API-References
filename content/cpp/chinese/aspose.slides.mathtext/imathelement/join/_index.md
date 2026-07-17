---
title: Join()
second_title: Aspose.Slides C++ API 参考
description: 将数学元素连接并形成数学块
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) 方法


将数学元素连接并形成数学块

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 要连接的元素 |

### 返回值

包含此实例和指定参数的新 [IMathBlock](../../imathblock/)

## 备注



示例： 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) 方法


将数学文本连接并形成数学块

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 要连接的数学文本 |

### 返回值

包含此实例和指定参数的新 [IMathBlock](../../imathblock/)

## 备注



示例： 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBlock](../../imathblock/)
* 类 [IMathElement](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)