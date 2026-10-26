---
title: RectangleF class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 矩形の位置とサイズを表す 4 つの浮動小数点数のセットを格納します。
type: docs
url: /ja/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF クラス

四つの浮動小数点数のセットを保持し、矩形の位置とサイズを表します。 .NET `System.Drawing.RectangleF` と互換性があります。

**継承:**[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/ja/aspose.slides/rectangle)

RectangleF 型は次のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/ja/aspose.slides/rectanglef/__init__/#float-float-float-float) | 指定された位置とサイズで矩形を作成します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`x`](/slides/python-net/ja/aspose.slides/rectanglef/x/) | この矩形の左上隅の x 座標を取得します。<br/>            読み取り専用 **float**. |
| [`y`](/slides/python-net/ja/aspose.slides/rectanglef/y/) | この矩形の左上隅の y 座標を取得します。<br/>            読み取り専用 **float**. |
| [`width`](/slides/python-net/ja/aspose.slides/rectanglef/width/) | この矩形の幅を取得します。<br/>            読み取り専用 **float**. |
| [`height`](/slides/python-net/ja/aspose.slides/rectanglef/height/) | この矩形の高さを取得します。<br/>            読み取り専用 **float**. |
| [`left`](/slides/python-net/ja/aspose.slides/rectanglef/left/) | この矩形の左端の x 座標を取得します。`x` と等しいです。<br/>            読み取り専用 **float**. |
| [`top`](/slides/python-net/ja/aspose.slides/rectanglef/top/) | この矩形の上端の y 座標を取得します。`y` と等しいです。<br/>            読み取り専用 **float**. |
| [`right`](/slides/python-net/ja/aspose.slides/rectanglef/right/) | この矩形の `x` と `width` の合計である x 座標を取得します。<br/>            読み取り専用 **float**. |
| [`bottom`](/slides/python-net/ja/aspose.slides/rectanglef/bottom/) | この矩形の `y` と `height` の合計である y 座標を取得します。<br/>            読み取り専用 **float**. |
| [`is_empty`](/slides/python-net/ja/aspose.slides/rectanglef/is_empty/) | この矩形のすべての数値プロパティがゼロであるかどうかを指定します。<br/>            読み取り専用 **bool**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/ja/aspose.slides/rectanglef/contains/#float-float) | 指定された点がこの矩形に含まれているかどうかを判断します。 |
| [`contains(self, point)`](/slides/python-net/ja/aspose.slides/rectanglef/contains/#pointf) | 指定された点がこの矩形に含まれているかどうかを判断します。 |
| [`contains(self, rect)`](/slides/python-net/ja/aspose.slides/rectanglef/contains/#rectanglef) | `rect` で表される矩形領域がこの矩形に完全に含まれているかどうかを判断します。 |


### 備考

矩形は `==` 演算子で位置とサイズを比較し、辞書のキーや集合のメンバーとして使用できます。


### 参照
* クラス [`Rectangle`](/slides/python-net/ja/aspose.slides/rectangle)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)