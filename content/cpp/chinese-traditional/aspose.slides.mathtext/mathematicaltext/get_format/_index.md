---
title: get_Format()
second_title: Aspose.Slides for C++ API 參考
description: 文字格式屬性
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathematicaltext/get_format/
---
## MathematicalText::get_Format() 方法


文字格式屬性

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::MathematicalText::get_Format() override
```

## 備註


範例：
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 類別 [MathematicalText](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)