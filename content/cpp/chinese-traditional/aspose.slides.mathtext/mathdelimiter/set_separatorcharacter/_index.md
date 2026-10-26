---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API 參考
description: "分隔符號字元指定在分隔符物件中分隔參數的字元。預設值：'|'."
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) 方法


分隔符號字元指定在分隔符物件中分隔參數的字元。預設值：'|'。

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## 備註


範例： 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 參見

* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)