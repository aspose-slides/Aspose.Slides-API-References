---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API リファレンス
description: "Operator Emulator。true の場合、ボックスとその内容は単一の演算子として動作し、演算子のプロパティを継承します。つまり、例えばこの文字は改行位置として使用でき、他の演算子に合わせて配置できます。Operator Emulator は、'==' のように 1 つ以上のグリフが結合して演算子になる場合によく使用されます。デフォルト値: false"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() メソッド

Operator Emulator。true の場合、ボックスとその内容は単一の演算子として動作し、演算子のプロパティを継承します。つまり、例えばこの文字は改行位置として使用でき、他の演算子に揃えることができます。Operator Emulator は、'==' のように 1 つ以上のグリフが組み合わさって演算子になる場合によく使用されます。デフォルト値: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
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
* ライブラリ [Aspose.Slides](../../../)