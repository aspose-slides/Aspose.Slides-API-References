---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API 參考
description: "Delimiter Beginning Character 指定起始或開啟的分隔符字符。數學分隔符是用於包圍的字符，例如括號、方括號和大括號。預設值為 '('。"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() 方法


Delimiter Beginning Character 指定起始或開啟的分隔符字符。數學分隔符是用於包圍的字符，例如括號、方括號和大括號。預設值為 '('。

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## 備註


範例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## 參見

* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)