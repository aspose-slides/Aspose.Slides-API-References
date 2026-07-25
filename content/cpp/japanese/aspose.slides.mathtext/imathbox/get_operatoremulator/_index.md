---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API リファレンス
description: "Operator Emulator. true の場合、ボックスとその内容は単一の演算子として動作し、演算子のプロパティを継承します。この意味は、たとえば文字が改行位置として機能し、他の演算子に揃えることができるということです。Operator Emulators は、'==' のように 1 つまたは複数のグリフが結合して演算子を形成する場合によく使用されます。デフォルト値: false"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() メソッド


Operator Emulator. true の場合、ボックスとその内容は単一の演算子として動作し、演算子のプロパティを継承します。この意味は、たとえば文字が改行位置として機能し、他の演算子に揃えることができるということです。Operator Emulators は、'==' のように 1 つまたは複数のグリフが結合して演算子を形成する場合によく使用されます。デフォルト値: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## 備考


例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## 参照

* クラス [IMathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)