---
title: get_R1C1Formula()
second_title: Aspose.Slides for C++ API リファレンス
description: R1C1 形式の数式を取得します。
type: docs
weight: 79
url: /ja/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() メソッド


R1C1 形式の数式を取得します。

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
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