---
title: get_EndingCharacter()
second_title: Aspose.Slides for C++ API 參考
description: "分隔符結束字符指定結束或閉合的分隔符字符。數學分隔符是括號、方括號和大括號等封閉字符。預設值：')'。"
type: docs
weight: 66
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() 方法


分隔符結束字符指定結束或閉合的分隔符字符。數學分隔符是括號、方括號和大括號等封閉字符。預設值：')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## 備註


範例: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 參見

* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)