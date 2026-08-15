---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API 參考
description: "分隔符開頭字元指定開始或開啟的分隔字符。數學分隔符是包圍字符，例如括號、方括號與大括號。預設值：'('。"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() 方法

Delimiter Beginning Character 指定開始或開啟的分界字元。數學分界符是包圍字符，例如括號、方括號與大括號。預設值：'('。

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## 備註

範例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## 另請參閱

* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)