---
title: IPictureFillFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat クラス

画像の塗りつぶしスタイルを表します。

IPictureFillFormat 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`dpi`](/slides/python-net/ja/aspose.slides/ipicturefillformat/dpi/) | 画像の塗りつぶしに使用される dpi を取得または設定します。<br/>            読み書き可能 **int**。 |
| [`picture_fill_mode`](/slides/python-net/ja/aspose.slides/ipicturefillformat/picture_fill_mode/) | 画像の塗りつぶしモードを取得または設定します。<br/>            読み書き可能 [`PictureFillMode`](/slides/python-net/ja/aspose.slides/picturefillmode)。 |
| [`picture`](/slides/python-net/ja/aspose.slides/ipicturefillformat/picture/) | 画像を取得します。<br/>            読み取り専用 [`ISlidesPicture`](/slides/python-net/ja/aspose.slides/islidespicture)。 |
| [`crop_left`](/slides/python-net/ja/aspose.slides/ipicturefillformat/crop_left/) | 実際の画像幅のパーセンテージ数で、画像の左側から切り取られる部分を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`crop_top`](/slides/python-net/ja/aspose.slides/ipicturefillformat/crop_top/) | 実際の画像高さのパーセンテージ数で、画像の上側から切り取られる部分を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`crop_right`](/slides/python-net/ja/aspose.slides/ipicturefillformat/crop_right/) | 実際の画像幅のパーセンテージ数で、画像の右側から切り取られる部分を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`crop_bottom`](/slides/python-net/ja/aspose.slides/ipicturefillformat/crop_bottom/) | 実際の画像高さのパーセンテージ数で、画像の下側から切り取られる部分を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`stretch_offset_left`](/slides/python-net/ja/aspose.slides/ipicturefillformat/stretch_offset_left/) | シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義された塗りつぶし矩形の左端を取得または設定します。<br/>            正のパーセンテージはインセットを、負のパーセンテージはアウトセットを指定します。<br/>            読み書き可能 **float**。 |
| [`stretch_offset_top`](/slides/python-net/ja/aspose.slides/ipicturefillformat/stretch_offset_top/) | シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義された塗りつぶし矩形の上端を取得または設定します。<br/>            正のパーセンテージはインセットを、負のパーセンテージはアウトセットを指定します。<br/>            読み書き可能 **float**。 |
| [`stretch_offset_right`](/slides/python-net/ja/aspose.slides/ipicturefillformat/stretch_offset_right/) | シェイプのバウンディングボックスの右端からのパーセンテージオフセットで定義された塗りつぶし矩形の右端を取得または設定します。<br/>            正のパーセンテージはインセットを、負のパーセンテージはアウトセットを指定します。<br/>            読み書き可能 **float**。 |
| [`stretch_offset_bottom`](/slides/python-net/ja/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | シェイプのバウンディングボックスの下端からのパーセンテージオフセットで定義された塗りつぶし矩形の下端を取得または設定します。<br/>            正のパーセンテージはインセットを、負のパーセンテージはアウトセットを指定します。<br/>            読み書き可能 **float**。 |
| [`tile_offset_x`](/slides/python-net/ja/aspose.slides/ipicturefillformat/tile_offset_x/) | テクスチャの水平方向オフセット（シェイプの原点からのポイント単位）を取得または設定します。<br/>            正の値はテクスチャを右へ、負の値は左へ移動させます。<br/>            読み書き可能 **float**。 |
| [`tile_offset_y`](/slides/python-net/ja/aspose.slides/ipicturefillformat/tile_offset_y/) | テクスチャの垂直方向オフセット（シェイプの原点からのポイント単位）を取得または設定します。<br/>            正の値はテクスチャを下へ、負の値は上へ移動させます。<br/>            読み書き可能 **float**。 |
| [`tile_scale_x`](/slides/python-net/ja/aspose.slides/ipicturefillformat/tile_scale_x/) | テクスチャ塗りつぶしの水平スケールをパーセンテージで取得または設定します。<br/>            読み書き可能 **float**。 |
| [`tile_scale_y`](/slides/python-net/ja/aspose.slides/ipicturefillformat/tile_scale_y/) | テクスチャ塗りつぶしの垂直スケールをパーセンテージで取得または設定します。<br/>            読み書き可能 **float**。 |
| [`tile_alignment`](/slides/python-net/ja/aspose.slides/ipicturefillformat/tile_alignment/) | テクスチャがシェイプ内でどのように配置されるかを取得または設定します。この設定はテクスチャパターンの開始点とシェイプ全体での繰り返し方法を制御します。<br/>            読み書き可能 [`RectangleAlignment`](/slides/python-net/ja/aspose.slides/rectanglealignment)。 |
| [`tile_flip`](/slides/python-net/ja/aspose.slides/ipicturefillformat/tile_flip/) | テクスチャタイルを水平、垂直、または両方の軸で反転させます。<br/>            読み書き可能 [`TileFlip`](/slides/python-net/ja/aspose.slides/tileflip)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/ja/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | シェイプのサイズと指定された解像度に基づいて画像のサイズを縮小し、画像を圧縮します。オプションで、切り取られた領域も削除します。 |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/ja/aspose.slides/ipicturefillformat/compress_image/#bool-float) | シェイプのサイズと指定された解像度に基づいて画像のサイズを縮小し、画像を圧縮します。オプションで、切り取られた領域も削除します。 |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/ja/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | 塗りつぶし画像の切り取られた領域を削除します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)