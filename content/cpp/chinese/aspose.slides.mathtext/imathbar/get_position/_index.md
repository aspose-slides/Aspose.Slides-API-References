---
title: get_Position()
second_title: Aspose.Slides for C++ API 参考
description: "栏线的位置。默认：顶部"
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() 方法


栏线的位置。默认：顶部

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## 备注


示例： 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 另见

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类 [IMathBar](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)