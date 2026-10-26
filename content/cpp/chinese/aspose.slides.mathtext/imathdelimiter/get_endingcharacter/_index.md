---
title: get_EndingCharacter()
second_title: Aspose.Slides for C++ API 参考
description: "Delimiter Ending Character 指定结束或闭合的分隔符字符。数学分隔符是诸如括号、方括号和大括号等包围字符。默认值: ')'."
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() 方法

Delimiter Ending Character 指定结束或闭合的分隔符字符。数学分隔符是诸如括号、方括号和大括号等包围字符。默认值: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```
## 备注

示例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 另请参见

* 类 [IMathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)