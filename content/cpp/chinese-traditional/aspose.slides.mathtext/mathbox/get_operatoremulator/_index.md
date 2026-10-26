---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API 參考
description: "Operator Emulator。當為 true 時，方框及其內容會作為單一運算子並繼承運算子的屬性。這表示，例如，該字元可以作為換行點，且可與其他運算子對齊。Operator Emulator 通常在一個或多個字形結合形成運算子時使用，例如 '=='. 預設值：false"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() 方法


Operator Emulator。當 true 時，方框及其內容會視為單一運算子，並繼承運算子的屬性。這表示，例如，該字元可以作為換行點，且可與其他運算子對齊。Operator Emulator 通常在一個或多個字形結合形成運算子時使用，例如 '=='。預設值：false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## 備註


範例：
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## 另見

* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)