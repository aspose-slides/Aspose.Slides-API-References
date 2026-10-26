---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API 參考
description: "分隔符開始字元指定起始或開啟的分隔符字元。數學分隔符是用於包圍的字元，例如括號、方括號和大括號。預設值： '('."
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) 方法

分隔符開始字元指定起始或開啟的分隔符字元。數學分隔符是用於包圍的字元，例如括號、方括號和大括號。預設值： '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
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
* 程式庫 [Aspose.Slides](../../../)