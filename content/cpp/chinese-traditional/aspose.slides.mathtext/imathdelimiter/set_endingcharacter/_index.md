---
title: set_EndingCharacter()
second_title: Aspose.Slides for C++ API 參考
description: "Delimiter Ending Character 指定結束或關閉的分隔字元。數學分隔符是用於包圍的字元，例如圓括號、方括號和大括號。預設為 ')'."
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) 方法

Delimiter Ending Character 指定結束或關閉的分隔字元。數學分隔符是用於包圍的字元，例如圓括號、方括號和大括號。預設為 ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## 備註

範例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 另見

* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)