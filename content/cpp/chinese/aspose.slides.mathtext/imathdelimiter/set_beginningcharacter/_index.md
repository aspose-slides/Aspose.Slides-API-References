---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API 参考
description: "分隔符起始字符指定开始或打开的分隔符字符。数学分隔符是诸如圆括号、方括号和大括号之类的包围字符。默认值: '('."
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) 方法


分隔符起始字符指定开始或打开的分隔符字符。数学分隔符是诸如圆括号、方括号和大括号之类的包围字符。默认值: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## 备注


示例:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## 另请参阅

* 类 [IMathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)