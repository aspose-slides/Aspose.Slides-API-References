---
title: set_Position()
second_title: Aspose.Slides 的 C++ API 参考
description: "条形线的位置。默认：Top"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathbar/set_position/
---
## MathBar::set_Position(MathTopBotPositions) 方法


条形线的位置。默认：Top

```cpp
void Aspose::Slides::MathText::MathBar::set_Position(MathTopBotPositions value) override
```

## 备注


示例：
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 另见

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类 [MathBar](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)