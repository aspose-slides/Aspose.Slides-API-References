---
title: set_OperatorEmulator()
second_title: Aspose.Slides for C++ API リファレンス
description: "Operator Emulator. true の場合、ボックスとその内容は単一の演算子として動作し、演算子のプロパティを継承します。例えば、この文字は改行位置として機能し、他の演算子に揃えることができます。Operator Emulators は、'==' のように複数の字形が結合して演算子になる場合に頻繁に使用されます。デフォルト値: false"
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) method

Operator Emulator. true の場合、ボックスとその内容は単一の演算子として動作し、演算子のプロパティを継承します。例えば、この文字は改行位置として機能し、他の演算子に揃えることができます。Operator Emulators は、'==' のように複数の字形が結合して演算子になる場合に頻繁に使用されます。デフォルト値: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## 備考

例: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## 参照

* クラス [MathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)