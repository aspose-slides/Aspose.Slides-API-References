---
title: Rectangle class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 矩形の位置とサイズを表す4つの整数のセットを格納します。
type: docs
url: /ja/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle クラス

四つの整数で矩形の位置とサイズを表します。.NET の `System.Drawing.Rectangle` と互換性があります。

Rectangle 型は次のメンバーを公開します。

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/ja/aspose.slides/rectangle/__init__/#int-int-int-int) | 指定された位置とサイズで矩形を作成します。浮動小数点値は整数に切り捨てられます。 |

## プロパティ

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/ja/aspose.slides/rectangle/x/) | この矩形の左上隅の x 座標を取得します。<br/>            読み取り専用 **int**. |
| [`y`](/slides/python-net/ja/aspose.slides/rectangle/y/) | この矩形の左上隅の y 座標を取得します。<br/>            読み取り専用 **int**. |
| [`width`](/slides/python-net/ja/aspose.slides/rectangle/width/) | この矩形の幅を取得します。<br/>            読み取り専用 **int**. |
| [`height`](/slides/python-net/ja/aspose.slides/rectangle/height/) | この矩形の高さを取得します。<br/>            読み取り専用 **int**. |
| [`left`](/slides/python-net/ja/aspose.slides/rectangle/left/) | この矩形の左端の x 座標を取得します。`x` と同じです。<br/>            読み取り専用 **int**. |
| [`top`](/slides/python-net/ja/aspose.slides/rectangle/top/) | この矩形の上端の y 座標を取得します。`y` と同じです。<br/>            読み取り専用 **int**. |
| [`right`](/slides/python-net/ja/aspose.slides/rectangle/right/) | この矩形の `x` と `width` の合計である x 座標を取得します。<br/>            読み取り専用 **int**. |
| [`bottom`](/slides/python-net/ja/aspose.slides/rectangle/bottom/) | この矩形の `y` と `height` の合計である y 座標を取得します。<br/>            読み取り専用 **int**. |
| [`is_empty`](/slides/python-net/ja/aspose.slides/rectangle/is_empty/) | この矩形のすべての数値プロパティが 0 の場合に true を返します。<br/>            読み取り専用 **bool**. |

## メソッド

| Method | Description |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/ja/aspose.slides/rectangle/contains/#int-int) | 指定された点がこの矩形に含まれるかどうかを判定します。 |
| [`contains(self, point)`](/slides/python-net/ja/aspose.slides/rectangle/contains/#point) | 指定された点がこの矩形に含まれるかどうかを判定します。 |
| [`contains(self, rect)`](/slides/python-net/ja/aspose.slides/rectangle/contains/#rectangle) | `rect` で表される矩形領域がこの矩形に完全に含まれるかどうかを判定します。 |

### 備考

矩形は `==` によって位置とサイズで比較され、辞書キーや集合の要素として使用できます。

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)