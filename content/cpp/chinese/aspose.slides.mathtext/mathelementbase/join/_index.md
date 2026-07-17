---
title: Join()
second_title: Aspose.Slides C++ API 参考
description: 将数学元素连接起来并形成数学块
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) 方法

将数学元素连接起来并形成数学块

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要加入的元素 |

### 返回值

包含此实例和指定参数的新[IMathBlock](../../imathblock/)

## 备注

示例：
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) 方法

将数学文本连接起来并形成数学块

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 要加入的数学文本 |

### 返回值

包含此实例和指定参数的新[IMathBlock](../../imathblock/)

## 备注

示例：
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBlock](../../imathblock/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)