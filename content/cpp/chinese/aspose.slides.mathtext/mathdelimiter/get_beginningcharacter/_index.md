---
title: get_BeginningCharacter()
second_title: Aspose.Slides C++ API 参考
description: "分隔符起始字符指定开始或打开的分隔符字符。数学分隔符是诸如圆括号、方括号和大括号等包围字符。默认值：'('。"
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() 方法


分隔符起始字符指定起始或开头的分隔符字符。数学分隔符是诸如圆括号、方括号和大括号等包围字符。默认：'('。

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
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