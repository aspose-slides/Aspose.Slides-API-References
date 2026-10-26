---
title: Enclose()
second_title: Aspose.Slides for C++ API 参考
description: 将数学元素用括号括起来
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() 方法

将数学元素用括号括起来

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```

### 返回值

包含括号的类型为 [IMathDelimiter](../../imathdelimiter/) 的数学元素

## 备注



示例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) 方法

使用指定字符（如括号或其他字符）将数学元素框住

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| beginningCharacter | char16_t | 起始字符（通常为左括号） |
| endingCharacter | char16_t | 结束字符（通常为右括号） |

### 返回值

使用指定字符进行框定的类型为 [IMathDelimiter](../../imathdelimiter/) 的数学元素

## 备注



示例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathDelimiter](../../imathdelimiter/)
* 类 [MathElementBase](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)