---
title: DoubleChartValue class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/doublechartvalue/
---
## DoubleChartValue クラス

pptx プレゼンテーション ドキュメントに格納できる double 値を 2 つの方法で表します:
1) チャートに関連付けられたブックのセル/セル 群に格納する;
2) リテラル値として格納する。

**継承:**[`DoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/doublechartvalue) → [`BaseChartValue`](/slides/python-net/ja/aspose.slides.charts/basechartvalue)

DoubleChartValue 型は次のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`data_source_type`](/slides/python-net/ja/aspose.slides.charts/doublechartvalue/data_source_type/) | 子クラスで実際に使用されている AsCell、AsCells、AsLiteralString、または AsLiteralDouble <br/>            プロパティかどうかを指定します。言い換えれば、Data プロパティの値の型を指定します。<br/>            Read/write [`DataSourceType`](/slides/python-net/ja/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/ja/aspose.slides.charts/doublechartvalue/data/) | Data オブジェクトを取得または設定します。<br/>            Read/write **any**. |
| [`as_cell`](/slides/python-net/ja/aspose.slides.charts/doublechartvalue/as_cell/) | チャート データ セルを取得または設定します。<br/>            Read/write [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell). |
| [`as_literal_double`](/slides/python-net/ja/aspose.slides.charts/doublechartvalue/as_literal_double/) | リテラル double 値を取得または設定します。<br/>            Read/write **float**. |

## メソッド

| Method | Description |
| :- | :- |
| [`to_double(self)`](/slides/python-net/ja/aspose.slides.charts/doublechartvalue/to_double/#) | **float** に変換します。 |

### 関連項目
* クラス [`BaseChartValue`](/slides/python-net/ja/aspose.slides.charts/basechartvalue)
* クラス [`DoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/doublechartvalue)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)