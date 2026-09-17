---
title: IColorFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icolorformat/
---
## IColorFormat クラス

プレゼンテーションで使用される色を表します。

IColorFormat 型は以下のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`color_type`](/slides/python-net/ja/aspose.slides/icolorformat/color_type/) | 色定義方法を取得または設定します。<br/>            読み取り/書き込み [`ColorType`](/slides/python-net/ja/aspose.slides/colortype). |
| [`color`](/slides/python-net/ja/aspose.slides/icolorformat/color/) | すべての色変換が適用された結果の色を取得します。<br/>            RGB 色を設定し、すべての色変換をクリアします。<br/>            読み取り/書き込み **aspose.slides.Color**. |
| [`preset_color`](/slides/python-net/ja/aspose.slides/icolorformat/preset_color/) | カラープリセットを取得または設定します。<br/>            読み取り/書き込み [`PresetColor`](/slides/python-net/ja/aspose.slides/presetcolor). |
| [`system_color`](/slides/python-net/ja/aspose.slides/icolorformat/system_color/) | システムカラー テーブルで識別される色を取得または設定します。<br/>            読み取り/書き込み [`SystemColor`](/slides/python-net/ja/aspose.slides/systemcolor). |
| [`scheme_color`](/slides/python-net/ja/aspose.slides/icolorformat/scheme_color/) | カラースキームで識別される色を取得または設定します。<br/>            読み取り/書き込み [`SchemeColor`](/slides/python-net/ja/aspose.slides/schemecolor). |
| [`r`](/slides/python-net/ja/aspose.slides/icolorformat/r/) | 色の赤成分を取得または設定します。すべての色変換は無視されます。<br/>            読み取り/書き込み **int**. |
| [`g`](/slides/python-net/ja/aspose.slides/icolorformat/g/) | 色の緑成分を取得または設定します。すべての色変換は無視されます。<br/>            読み取り/書き込み **int**. |
| [`b`](/slides/python-net/ja/aspose.slides/icolorformat/b/) | 色の青成分を取得または設定します。すべての色変換は無視されます。<br/>            読み取り/書き込み **int**. |
| [`float_r`](/slides/python-net/ja/aspose.slides/icolorformat/float_r/) | 色の赤成分を取得または設定します。すべての色変換は無視されます。<br/>            読み取り/書き込み **float**. |
| [`float_g`](/slides/python-net/ja/aspose.slides/icolorformat/float_g/) | 色の緑成分を取得または設定します。すべての色変換は無視されます。<br/>            読み取り/書き込み **float**. |
| [`float_b`](/slides/python-net/ja/aspose.slides/icolorformat/float_b/) | 色の青成分を取得または設定します。すべての色変換は無視されます。<br/>            読み取り/書き込み **float**. |
| [`hue`](/slides/python-net/ja/aspose.slides/icolorformat/hue/) | HSL 表現における色の色相成分を取得または設定します。<br/>            すべての色変換は無視されます。<br/>            読み取り/書き込み **float**. |
| [`saturation`](/slides/python-net/ja/aspose.slides/icolorformat/saturation/) | HSL 表現における色の彩度成分を取得または設定します。<br/>            すべての色変換は無視されます。<br/>            読み取り/書き込み **float**. |
| [`luminance`](/slides/python-net/ja/aspose.slides/icolorformat/luminance/) | HSL 表現における色の明度成分を取得または設定します。<br/>            すべての色変換は無視されます。<br/>            読み取り/書き込み **float**. |
| [`color_transform`](/slides/python-net/ja/aspose.slides/icolorformat/color_transform/) | 色に適用された色変換のコレクションを取得します。<br/>            読み取り専用 [`IColorOperationCollection`](/slides/python-net/ja/aspose.slides/icoloroperationcollection). |

## メソッド

| Method | Description |
| :- | :- |
| [`to_string(self, format)`](/slides/python-net/ja/aspose.slides/icolorformat/to_string/#colorstringformat) | 現在のカラーフォーマットを表す **str** を取得します。 |
| [`copy_from(self, color)`](/slides/python-net/ja/aspose.slides/icolorformat/copy_from/#icolorformat) | "color" からカラーフォーマットをコピーします。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)