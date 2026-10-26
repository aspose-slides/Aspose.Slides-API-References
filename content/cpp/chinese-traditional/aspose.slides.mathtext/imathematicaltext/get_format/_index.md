---
title: get_Format()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 文字格式屬性
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() 方法

文字格式屬性

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## 備註


範例： 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## 參見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 類別 [IMathematicalText](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)