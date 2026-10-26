---
title: set_OperatorEmulator()
second_title: Aspose.Slides for C++ API 參考
description: "運算子模擬器。當為 true 時，盒子及其內容會作為單一運算子運作，並繼承運算子的屬性。這意味著，例如，該字元可以作為換行點，並可對齊至其他運算子。運算子模擬器常用於一個或多個字形組合成運算子，例如 '=='。預設值：false"
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) 方法


運算子模擬器。當為 true 時，盒子及其內容會表現為單一運算子，並繼承運算子的屬性。這意味著，例如，該字元可以作為換行點，並可對齊至其他運算子。運算子模擬器常用於一個或多個字形組合成運算子，例如 '=='。預設值：false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## 備註


範例:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## 另請參閱

* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)