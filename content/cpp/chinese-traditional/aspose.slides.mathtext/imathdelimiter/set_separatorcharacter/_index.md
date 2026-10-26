---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API 參考
description: "分隔符號字符指定在分隔符物件中用來分隔參數的字符。預設值：'|'."
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) method


分隔符號字符指定在分隔符物件中用來分隔參數的字符。預設值：'|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## 備註


範例： 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 另請參閱

* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)