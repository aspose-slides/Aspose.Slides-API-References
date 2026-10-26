---
title: set_EndingCharacter()
second_title: Aspose.Slides for C++ API 参考
description: "分隔符结束字符指定结束或闭合的分隔符字符。数学分隔符是诸如括号、方括号和大括号等包围字符。默认: ')'."
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) 方法

Delimiter Ending Character 指定结束或闭合的分隔符字符。数学分隔符是诸如括号、方括号和大括号等包围字符。默认值: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## 备注

示例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 另请参见

* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)