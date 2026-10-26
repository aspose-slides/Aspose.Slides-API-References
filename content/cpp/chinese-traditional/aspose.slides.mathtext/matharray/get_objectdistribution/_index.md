---
title: get_ObjectDistribution()
second_title: Aspose.Slides for C++ API 參考
description: Object Distribution 為 true 時，陣列的內容會依據陣列物件的最大寬度進行間距調整。
type: docs
weight: 66
url: /zh-hant/aspose.slides.mathtext/matharray/get_objectdistribution/
---
## MathArray::get_ObjectDistribution() 方法

Object Distribution 為 true 時，陣列的內容會依據陣列物件的最大寬度進行間距調整。

```cpp
bool Aspose::Slides::MathText::MathArray::get_ObjectDistribution() override
```

## 備註


範例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_ObjectDistribution(true);
```

## 另請參閱

* 類別 [MathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)