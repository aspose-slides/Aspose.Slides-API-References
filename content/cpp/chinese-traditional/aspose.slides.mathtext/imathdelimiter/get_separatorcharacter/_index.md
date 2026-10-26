---
title: get_SeparatorCharacter()
second_title: Aspose.Slides for C++ API 參考文件
description: "分隔符號字符指定在分隔符物件中用於分隔參數的字符。預設值：'|'。"
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() 方法

分隔符號字符指定在分隔符物件中用於分隔參數的字符。預設值：'|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
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
* 程式庫 [Aspose.Slides](../../../)