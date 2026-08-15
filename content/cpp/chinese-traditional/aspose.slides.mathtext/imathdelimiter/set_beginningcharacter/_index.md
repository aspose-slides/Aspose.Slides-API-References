---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API 參考
description: "分隔符起始字符指定起始或開啟的分隔符字符。數學分隔符是用於封閉的字符，例如圓括號、方括號和大括號。預設值：'('。"
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) 方法

Delimiter Beginning Character 指定起始或開啟的分隔符字符。數學分隔符是用於封閉的字符，例如圓括號、方括號和大括號。預設值：'('。

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## 備註

範例:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## 參見

* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)