---
title: set_OperatorEmulator()
second_title: Aspose.Slides for C++ API 參考
description: "運算子模擬器。當設定為 true 時，盒子及其內容會作為單一運算子行為，並繼承運算子的屬性。這表示，例如，該字符可作為換行點，且可與其他運算子對齊。運算子模擬器常在一個或多個字形結合形成運算子（例如 '=='）時使用。預設值：false"
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) 方法

運算子模擬器。當值為 true 時，盒子及其內容會作為單一運算子行為，並繼承運算子的屬性。這表示，例如，該字符可作為換行點，且可與其他運算子對齊。運算子模擬器常在一個或多個字形結合形成運算子（例如 '=='）時使用。預設值：false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
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