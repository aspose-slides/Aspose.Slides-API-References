---
title: get_Limit()
second_title: Aspose.Slides for C++ API リファレンス
description: 上限引数
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() メソッド


上限引数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## 備考


例: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathLimit](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)