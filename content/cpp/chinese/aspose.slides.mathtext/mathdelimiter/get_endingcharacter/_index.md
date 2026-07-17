---
title: get_EndingCharacter()
second_title: Aspose.Slides C++ API 参考
description: "分隔符结束字符指定结束或关闭的分隔符字符。数学分隔符是诸如括号、方括号和大括号等封闭字符。默认值：')'。"
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() 方法


Delimiter Ending Character 指定结束或关闭的分隔符字符。数学分隔符是诸如括号、方括号和大括号等封闭字符。默认值：')'。

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## 备注


示例: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 另见

* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)