---
title: get_UpperLimit()
second_title: Aspose.Slides for C++ API リファレンス
description: 上限または下限を指定します
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() メソッド


上限または下限を指定します

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## 備考


例: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## 関連項目

* クラス [MathLimit](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)