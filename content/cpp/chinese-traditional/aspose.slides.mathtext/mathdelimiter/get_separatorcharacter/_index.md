---
title: get_SeparatorCharacter()
second_title: Aspose.Slides for C++ API 參考文件
description: "Delimiter Separator Character 指定分隔符物件中用來分隔參數的字元。預設值: '|'."
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() 方法

Delimiter Separator Character 指定分隔符物件中用來分隔參數的字元。預設值: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## 備註

範例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 另見

* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)