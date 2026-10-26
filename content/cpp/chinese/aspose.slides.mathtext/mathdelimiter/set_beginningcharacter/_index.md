---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API 参考
description: "Delimiter Beginning Character 指定起始或开启的分隔符字符。数学分隔符是诸如括号、方括号和大括号等包围字符。默认值: '('。"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) 方法

Delimiter Beginning Character 指定起始或开启的分隔符字符。数学分隔符是诸如括号、方括号和大括号等包围字符。默认值: '('。

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## 备注

示例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## 另请参见

* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)