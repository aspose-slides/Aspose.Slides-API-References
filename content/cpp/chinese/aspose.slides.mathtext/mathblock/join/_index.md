---
title: Join()
second_title: Aspose.Slides 的 C++ API 参考
description: 将数学元素与此数学块连接
type: docs
weight: 183
url: /zh/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) 方法

将数学元素与此数学块连接

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要加入的元素 |

### 返回值

当前 [IMathBlock](../../imathblock/) 实例

## 备注

示例： 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) 方法

将数学文本与此数学块连接

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 要加入的数学文本 |

### 返回值

一个包含此实例和指定参数的新 [IMathBlock](../../imathblock/)

## 备注

示例： 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBlock](../../imathblock/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathBlock](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)