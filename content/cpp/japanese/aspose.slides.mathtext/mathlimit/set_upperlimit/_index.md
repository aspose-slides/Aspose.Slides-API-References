---
title: set_UpperLimit()
second_title: Aspose.Slides for C++ API リファレンス
description: 上限または下限を指定します
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(bool) メソッド

Specifies upper or lower limit
```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
```

## 備考

例: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## 参照

* クラス [MathLimit](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)