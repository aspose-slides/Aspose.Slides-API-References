---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API 參考文件
description: "Operator Emulator。當為 true 時，方框及其內容會作為單一運算子運作，並繼承運算子的屬性。這表示，例如，該字元可作為換行點，並可與其他運算子對齊。當一個或多個字形結合形成運算子（例如 '=='）時，通常會使用 Operator Emulators。預設值：false"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() 方法

Operator Emulator. 當其為 true 時，方框及其內容會作為單一運算子運作，並繼承運算子的屬性。這表示，例如，該字元可以作為換行點，並可與其他運算子對齊。當一個或多個字形結合形成運算子（例如 '=='）時，常會使用 Operator Emulators。預設值：false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## 備註

範例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## 另請參閱

* 類別 [IMathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)