---
title: Enclose()
second_title: Aspose.Slides for C++ API 参考
description: 在括号中封装数学元素
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() 方法


在括号中封装数学元素

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### 返回值

包含括号的 [IMathDelimiter](../../imathdelimiter/) 类型的数学元素
## 备注



示例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) 方法


使用指定字符（如括号或其他字符）将此元素封装起来作为框架

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| beginningCharacter | char16_t | 起始字符（通常为左括号） |
| endingCharacter | char16_t | 结束字符（通常为右括号） |

### 返回值

包含指定字符作为框架的 [IMathDelimiter](../../imathdelimiter/) 类型的数学元素
## 备注



示例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathDelimiter](../../imathdelimiter/)
* 类 [IMathElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)