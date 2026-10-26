---
title: set_Formula()
second_title: Aspose.Slides for C++ API リファレンス
description: A1 形式で数式を設定します。
type: docs
weight: 66
url: /ja/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) メソッド


A1 形式で数式を設定します。

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## 備考



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## 参照

* クラス [String](../../../system/string/)
* クラス [IChartDataCell](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)