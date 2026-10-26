---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API 參考文件
description: "明確斷行指定在 Box 物件的起始處是否有換行，使行在 Box 物件的起始處自動換行。它還指定先前一行數學文字中運算子的編號，該編號將作為目前行數學文字的對齊點。可能的取值：1..255。預設值：0（無明確斷行）。"
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) 方法

Explicit break 指定在 Box 物件的起始處是否有換行，使行在 Box 物件的起始處自動換行。指定先前一行數學文字中運算子的編號，該編號將作為目前行數學文字的對齊點。可能的取值：1..255 預設值：0（無明確斷行）

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## 備註

範例：
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 另請參閱

* 類別 [IMathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)