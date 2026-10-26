---
title: get_SeparatorCharacter()
second_title: Aspose.Slides C++ API 参考
description: "分隔符分隔字符指定在分隔符对象中分隔参数的字符。默认值：'|'."
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() 方法

分隔符分隔字符指定在分隔符对象中分隔参数的字符。默认值：'|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
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