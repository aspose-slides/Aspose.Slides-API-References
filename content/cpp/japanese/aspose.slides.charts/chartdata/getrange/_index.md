---
title: GetRange()
second_title: Aspose.Slides for C++ API リファレンス
description: チャート データ範囲を取得します。
type: docs
weight: 157
url: /ja/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() メソッド


チャート データ範囲を取得します。

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### 戻り値

セルのデータ範囲の数式。例: "Sheet1!$A$1:$C$4"
## 備考




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## 参照

* クラス [String](../../../system/string/)
* クラス [ChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)