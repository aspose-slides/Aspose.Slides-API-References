---
title: get_Formula()
second_title: Aspose.Slides for C++ API リファレンス
description: A1 形式の数式を取得します。
type: docs
weight: 53
url: /ja/aspose.slides.charts/chartdatacell/get_formula/
---
## ChartDataCell::get_Formula() メソッド


A1 形式の数式を取得します。

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_Formula() override
```

## 備考



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## 参照

* クラス [String](../../../system/string/)
* クラス [ChartDataCell](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)