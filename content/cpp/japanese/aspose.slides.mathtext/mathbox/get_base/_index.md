---
title: get_Base()
second_title: Aspose.Slides C++ 用 API リファレンス
description: Base 引数
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() メソッド


Base 引数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## 備考


例: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)