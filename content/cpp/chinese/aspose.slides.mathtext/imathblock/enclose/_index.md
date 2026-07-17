---
title: Enclose()
second_title: Aspose.Slides for C++ API 参考
description: 将此块的子元素用指定字符（如括号或其他字符）括起来，并使用分隔符字符进行分隔
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) 方法

Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| beginningCharacter | char16_t | 起始字符（通常为左括号） |
| endingCharacter | char16_t | 结束字符（通常为右括号） |
| separatorCharacter | char16_t | 分隔符字符 |

### 返回值

类型为[IMathDelimiter](../../imathdelimiter/)的数学元素，其中包含指定字符作为框架和分隔符

## 备注

示例：
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathDelimiter](../../imathdelimiter/)
* 类 [IMathBlock](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)