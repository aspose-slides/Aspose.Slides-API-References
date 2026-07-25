---
title: set_R1C1Formula()
second_title: Aspose.Slides for C++ API リファレンス
description: R1C1 形式で数式を設定します。
type: docs
weight: 92
url: /ja/aspose.slides.charts/ichartdatacell/set_r1c1formula/
---
## IChartDataCell::set_R1C1Formula(System::String) メソッド

R1C1 形式で数式を設定します。

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_R1C1Formula(System::String value)=0
```

## 備考



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 参照

* クラス [String](../../../system/string/)
* クラス [IChartDataCell](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)