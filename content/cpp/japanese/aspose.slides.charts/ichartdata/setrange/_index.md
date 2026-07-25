---
title: SetRange()
second_title: Aspose.Slides for C++ API リファレンス
description: チャート データ範囲を設定します。シリーズとカテゴリは新しいデータ範囲に基づいて更新されます。データ範囲内のシリーズ数がチャート データのシリーズ数を超える場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。
type: docs
weight: 157
url: /ja/aspose.slides.charts/ichartdata/setrange/
---
## IChartData::SetRange(System::String) メソッド


チャート データ範囲を設定します。シリーズとカテゴリは新しいデータ範囲に基づいて更新されます。データ範囲内のシリーズ数がチャート データのシリーズ数を超える場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetRange(System::String formula)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | セル データ範囲の数式です。例: \"Sheet1!$A$1:$C$4\" , \"SomeSheetName!A1:B100\", \"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5\". |

## 参照

* クラス [String](../../../system/string/)
* クラス [IChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)