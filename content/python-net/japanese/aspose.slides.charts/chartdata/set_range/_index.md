---
title: set_range method
second_title: Aspose.Slides for Python via .NET API リファレンス
description:
type: docs
url: /ja/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
チャートのデータ範囲を設定します。シリーズとカテゴリは新しいデータ範囲に基づいて更新されます。
データ範囲内のシリーズ数がチャートデータのシリーズ数を超える場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。


```python
def set_range(self, formula):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| formula | **str** | セルのデータ範囲式です。例: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula は None です。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていないチャートタイプ |
| **RuntimeError(Proxy error(ArgumentException))** | formula の形式が正しくありません。 |



### 参照
* クラス [`ChartData`](/slides/python-net/ja/aspose.slides.charts/chartdata)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)