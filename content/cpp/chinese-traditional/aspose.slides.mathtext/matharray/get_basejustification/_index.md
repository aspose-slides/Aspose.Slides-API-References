---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API 參考文件
description: "指定陣列相對於周圍文字的對齊方式。陣列外的文字可以與陣列物件的底部、頂部或中心對齊。預設值：Center"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() 方法

指定陣列相對於周圍文字的對齊方式。陣列外的文字可以與陣列物件的底部、頂部或中心對齊。預設值：Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## 備註

範例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## 另請參考

* 列舉 [MathVerticalAlignment](../../mathverticalalignment/)
* 類別 [MathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)