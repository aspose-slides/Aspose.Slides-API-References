---
title: SetRange()
second_title: Aspose.Slides for C++ API リファレンス
description: チャート データの範囲を設定します。シリーズとカテゴリは新しいデータ範囲に基づいて更新されます。データ範囲内のシリーズ数がチャート データのシリーズ数より多い場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。
type: docs
weight: 170
url: /ja/aspose.slides.charts/chartdata/setrange/
---
## ChartData::SetRange(System::String) メソッド

チャート データの範囲を設定します。シリーズとカテゴリは新しいデータ範囲に基づいて更新されます。データ範囲内のシリーズ数がチャート データのシリーズ数より多い場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。

```cpp
void Aspose::Slides::Charts::ChartData::SetRange(System::String formula) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | セルのデータ範囲の数式です。例: \"Sheet1!$A$1:$C$4\" , \"SomeSheetName!A1:B100\", \"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5\". |

## 参照

* クラス [String](../../../system/string/)
* クラス [ChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)