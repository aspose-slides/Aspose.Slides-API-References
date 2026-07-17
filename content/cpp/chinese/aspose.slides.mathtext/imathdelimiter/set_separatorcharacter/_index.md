---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API 参考
description: "分隔符分隔字符指定在分隔符对象中分隔参数的字符。默认值：'|'."
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) 方法

Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## 备注

示例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 参见

* 类 [IMathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)