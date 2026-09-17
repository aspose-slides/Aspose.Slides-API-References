---
title: GeometryPath class
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/geometrypath/
---
## GeometryPath クラス

GeometryShape のジオメトリ パスを表します

GeometryPath 型は次のメンバーを公開します：

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/geometrypath/__init__/#) | GeometryPath のインスタンスを作成します |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`path_data`](/slides/python-net/ja/aspose.slides/geometrypath/path_data/) | GeometryShape のジオメトリ パスをパス セグメントの配列として返します。 |
| [`fill_mode`](/slides/python-net/ja/aspose.slides/geometrypath/fill_mode/) | 塗りつぶしモードを設定します。 |
| [`stroke`](/slides/python-net/ja/aspose.slides/geometrypath/stroke/) | ストロークの外観を設定します。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/ja/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | パスの末尾に直線を追加します。 |
| [`line_to(self, x, y)`](/slides/python-net/ja/aspose.slides/geometrypath/line_to/#float-float) | パスの末尾に直線を追加します。 |
| [`line_to(self, point, index)`](/slides/python-net/ja/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | パスの指定された位置に直線を追加します。 |
| [`line_to(self, x, y, index)`](/slides/python-net/ja/aspose.slides/geometrypath/line_to/#float-float-int) | パスの指定された位置に直線を追加します。 |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/ja/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | パスの末尾に立方ベジェ曲線を追加します。 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/ja/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | パスの末尾に立方ベジェ曲線を追加します。 |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/ja/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | パスの指定された位置に立方ベジェ曲線を追加します。 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/ja/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | パスの指定された位置に立方ベジェ曲線を追加します。 |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/ja/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | パスの末尾に二次ベジェ曲線を追加します。 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/ja/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | パスの末尾に二次ベジェ曲線を追加します。 |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/ja/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | パスの指定された位置に二次ベジェ曲線を追加します。 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/ja/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | パスの指定された位置に二次ベジェ曲線を追加します。 |
| [`move_to(self, point)`](/slides/python-net/ja/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | 次のポイント位置を設定します。 |
| [`move_to(self, x, y)`](/slides/python-net/ja/aspose.slides/geometrypath/move_to/#float-float) | 次のポイント位置を設定します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/geometrypath/remove_at/#int) | ジオメトリ パスの指定インデックスのセグメントを削除します。 |
| [`close_figure(self)`](/slides/python-net/ja/aspose.slides/geometrypath/close_figure/#) | このパスの現在の図形を閉じます。 |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/ja/aspose.slides/geometrypath/arc_to/#float-float-float-float) | 指定された円弧をパスに追加します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)