---
title: get_EndingCharacter()
second_title: Aspose.Slides for C++ API 參考
description: "分隔符結尾字符指定結束或關閉的分隔符字符。數學分隔符是諸如括號、方括號和大括號之類的包圍字符。預設值：')'。"
type: docs
weight: 66
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() 方法

分隔符結尾字符指定結束或關閉的分隔符字符。數學分隔符是諸如括號、方括號和大括號之類的包圍字符。預設值：')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## 備註

範例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 另見

* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)