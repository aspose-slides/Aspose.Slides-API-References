---
title: get_SeparatorCharacter()
second_title: Aspose.Slides C++ API 参考
description: "Delimiter Separator Character 指定分隔符对象中用于分隔参数的字符。默认值为：'|'。"
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() 方法


Delimiter Separator Character 指定分隔符对象中用于分隔参数的字符。默认值为：'|'。

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## 备注


示例： 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 另请参阅

* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)