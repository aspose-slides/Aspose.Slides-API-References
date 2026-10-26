---
title: get_Base()
second_title: Aspose.Slides C++ 用 API リファレンス
description: Base 引数
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathbar/get_base/
---
## MathBar::get_Base() メソッド

Base 引数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBar::get_Base() override
```

## 備考


例: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBar](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)