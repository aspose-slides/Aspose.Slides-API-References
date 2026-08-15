---
title: set_EndingCharacter()
second_title: Aspose.Slides for C++ API 參考文件
description: "Delimiter Ending Character 指定結束或關閉的分隔字元。數學分隔符是用於括住內容的字符，例如圓括號、方括號和大括號。預設值：')'."
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) 方法

Delimiter Ending Character 指定結束或關閉的分隔字元。Mathematical delimiters 是用於括住內容的字符，例如圓括號、方括號和大括號。預設值：')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## 備註


範例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 參見

* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)