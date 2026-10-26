---
title: set_SeparatorCharacter()
second_title: Aspose.Slides C++ API 参考
description: "分隔符分隔字符指定在分隔符对象中分隔参数的字符。默认值：'|'."
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) 方法

分隔符分隔字符指定在分隔符对象中分隔参数的字符。默认值：'|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## 备注

示例:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 另请参阅

* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)