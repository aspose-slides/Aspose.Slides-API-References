---
title: ChartTitle class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/charttitle/
---
## ChartTitle クラス

チャート タイトルのプロパティを表します。

ChartTitle 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`x`](/slides/python-net/ja/aspose.slides.charts/charttitle/x/) | タイトルの x 座標をチャートの幅の割合として取得または設定します。<br/>            読み取り/書き込み **float**. |
| [`y`](/slides/python-net/ja/aspose.slides.charts/charttitle/y/) | タイトルの y 座標をチャートの高さの割合として取得または設定します。<br/>            読み取り/書き込み **float**. |
| [`width`](/slides/python-net/ja/aspose.slides.charts/charttitle/width/) | タイトルの幅をチャートの幅の割合として取得または設定します。<br/>            読み取り/書き込み **float**. |
| [`height`](/slides/python-net/ja/aspose.slides.charts/charttitle/height/) | タイトルの高さをチャートの高さの割合として取得または設定します。<br/>            読み取り/書き込み **float**. |
| [`right`](/slides/python-net/ja/aspose.slides.charts/charttitle/right/) | 右。<br/>            読み取り専用 **float**. |
| [`bottom`](/slides/python-net/ja/aspose.slides.charts/charttitle/bottom/) | 下。<br/>            読み取り専用 **float**. |
| [`overlay`](/slides/python-net/ja/aspose.slides.charts/charttitle/overlay/) | 他のチャート要素がタイトルと重なることを許可するかどうかを決定します。<br/>            読み取り/書き込み **bool**. |
| [`format`](/slides/python-net/ja/aspose.slides.charts/charttitle/format/) | タイトルの塗りつぶし、線、エフェクト スタイルを取得します。<br/>            読み取り専用 [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/ja/aspose.slides.charts/charttitle/text_frame_for_overriding/) | リッチ形式のテキストを保持できます。このプロパティが None でない場合、この<br/>            フォーマット済みテキストの値は自動生成テキストを上書きします。<br/>            自動生成テキストはデータ ラベル、値軸の表示単位ラベル、軸タイトル、チャート タイトル、トレンドラインのラベルの暗黙のプロパティです。<br/>            自動生成テキストは IFormattedTextContainer.TextFormat プロパティでフォーマットされます。<br/>            読み取り専用 [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ja/aspose.slides.charts/charttitle/text_format/) | テキスト形式を取得します。<br/>            読み取り専用 [`IChartTextFormat`](/slides/python-net/ja/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/ja/aspose.slides.charts/charttitle/actual_x/) | チャート要素の実際の x 位置（左）を、チャートの左上隅に対する相対位置で指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。<br/>            読み取り **float**. |
| [`actual_y`](/slides/python-net/ja/aspose.slides.charts/charttitle/actual_y/) | チャート要素の実際の上位置を、チャートの左上隅に対する相対位置で指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。<br/>            読み取り **float**. |
| [`actual_width`](/slides/python-net/ja/aspose.slides.charts/charttitle/actual_width/) | チャート要素の実際の幅を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。<br/>            読み取り **float**. |
| [`actual_height`](/slides/python-net/ja/aspose.slides.charts/charttitle/actual_height/) | チャート要素の実際の高さを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。<br/>            読み取り **float**. |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/charttitle/chart/) | 親チャートを取得します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/charttitle/presentation/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ja/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | パラメータ "text" のテキストで TextFrameForOverriding を初期化します。<br/>            TextFrameForOverriding がすでに初期化されている場合は、単にそのテキストを変更します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)