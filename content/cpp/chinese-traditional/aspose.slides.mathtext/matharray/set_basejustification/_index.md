---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API 參考
description: "指定陣列相對於周圍文字的對齊方式。陣列外的文字可以與陣列物件的底部、頂部或中間對齊。預設值：Center"
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) 方法

指定陣列相對於周圍文字的對齊方式。陣列外的文字可以與陣列物件的底部、頂部或中心對齊。預設值：Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## 備註


範例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## 另見

* 列舉 [MathVerticalAlignment](../../mathverticalalignment/)
* 類別 [MathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)