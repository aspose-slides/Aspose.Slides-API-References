---
title: set_Position()
second_title: Aspose.Slides C++ API 参考
description: "条线的位置。默认：顶部"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathbar/set_position/
---
## IMathBar::set_Position(MathTopBotPositions) 方法


条线的位置。默认：顶部

```cpp
virtual void Aspose::Slides::MathText::IMathBar::set_Position(MathTopBotPositions value)=0
```

## 备注


示例：
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 另请参阅

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类 [IMathBar](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)