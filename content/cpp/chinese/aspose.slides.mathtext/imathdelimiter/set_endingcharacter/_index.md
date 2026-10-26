---
title: set_EndingCharacter()
second_title: Aspose.Slides for C++ API 参考
description: "分隔符结束字符指定结束或关闭的分隔符字符。数学分隔符是括号、方括号和大括号等包围字符。默认值：')'。"
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) 方法


分隔符结束字符指定结束或闭合的分隔符字符。数学分隔符是括号、方括号和大括号等包围字符。默认值：')'。

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## 备注


示例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 另请参阅

* 类 [IMathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)