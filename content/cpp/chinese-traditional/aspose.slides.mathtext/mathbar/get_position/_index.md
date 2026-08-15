---
title: get_Position()
second_title: Aspose.Slides for C++ API 參考
description: "條形線的位置。預設：上方"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathbar/get_position/
---
## MathBar::get_Position() 方法


條形線的位置。預設: 上方

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathBar::get_Position() override
```

## 備註


範例: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 參見

* 列舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 類別 [MathBar](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)