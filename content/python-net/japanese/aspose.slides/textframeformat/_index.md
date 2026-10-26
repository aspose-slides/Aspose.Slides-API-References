---
title: TextFrameFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/textframeformat/
---
## TextFrameFormat クラス

TextFrame の formatTextFrameFormatting プロパティを含みます。

**継承:**[`TextFrameFormat`](/slides/python-net/ja/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)

TextFrameFormat 型は次のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/textframeformat/__init__/#) | [`TextFrameFormat`](/slides/python-net/ja/aspose.slides/textframeformat) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/textframeformat/three_d_format/) | テキストの 3D 効果プロパティを表す ThreeDFormat オブジェクトを返します。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`margin_left`](/slides/python-net/ja/aspose.slides/textframeformat/margin_left/) | TextFrame の左余白（ポイント）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`margin_right`](/slides/python-net/ja/aspose.slides/textframeformat/margin_right/) | TextFrame の右余白（ポイント）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`margin_top`](/slides/python-net/ja/aspose.slides/textframeformat/margin_top/) | TextFrame の上余白（ポイント）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`margin_bottom`](/slides/python-net/ja/aspose.slides/textframeformat/margin_bottom/) | TextFrame の下余白（ポイント）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`wrap_text`](/slides/python-net/ja/aspose.slides/textframeformat/wrap_text/) | テキストが TextFrame の余白で折り返されている場合は **True**。<br/>            読み取り/書き込み [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool)。 |
| [`anchoring_type`](/slides/python-net/ja/aspose.slides/textframeformat/anchoring_type/) | TextFrame の垂直アンカー テキストを取得または設定します。<br/>            読み取り/書き込み [`TextAnchorType`](/slides/python-net/ja/aspose.slides/textanchortype)。 |
| [`center_text`](/slides/python-net/ja/aspose.slides/textframeformat/center_text/) | NullableBool.True の場合、テキストは横方向にボックス内で中央揃えになるべきです。<br/>            読み取り/書き込み [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool)。 |
| [`text_vertical_type`](/slides/python-net/ja/aspose.slides/textframeformat/text_vertical_type/) | テキストの向きを決定します。<br/>            このプロパティとプロパティ RotationAngle のカスタム角度からまとめられた視覚的テキスト回転の結果値。<br/>            読み取り/書き込み [`TextVerticalType`](/slides/python-net/ja/aspose.slides/textverticaltype)。 |
| [`autofit_type`](/slides/python-net/ja/aspose.slides/textframeformat/autofit_type/) | テキストの自動調整モードを取得または設定します。<br/>            読み取り/書き込み [`TextAutofitType`](/slides/python-net/ja/aspose.slides/textautofittype)。 |
| [`column_count`](/slides/python-net/ja/aspose.slides/textframeformat/column_count/) | テキスト領域の列数を取得または設定します。<br/>            この値は正の数である必要があります。そうでない場合、値は 0 に設定されます。<br/>            値 0 は未定義を意味します。<br/>            読み取り/書き込み **int**。 |
| [`column_spacing`](/slides/python-net/ja/aspose.slides/textframeformat/column_spacing/) | テキスト領域内のテキスト列間の間隔（ポイント）を取得または設定します。これは列が 1 つ以上ある場合にのみ適用されます。<br/>            この値は正の数である必要があります。そうでない場合、値は 0 に設定されます。<br/>            読み取り/書き込み **float**。 |
| [`rotation_angle`](/slides/python-net/ja/aspose.slides/textframeformat/rotation_angle/) | バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合、付随するシェイプの回転が使用されます。指定された場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されると同時に、テキスト自体にも回転が適用されます。<br/>            このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプからまとめられた視覚的テキスト回転の結果値。<br/>            読み取り/書き込み **float**。 |
| [`transform`](/slides/python-net/ja/aspose.slides/textframeformat/transform/) | テキストの折り返し形状を取得または設定します。<br/>            読み取り/書き込み [`TextShapeType`](/slides/python-net/ja/aspose.slides/textshapetype)。 |
| [`keep_text_flat`](/slides/python-net/ja/aspose.slides/textframeformat/keep_text_flat/) | 3D 回転効果が適用されてもテキストを平坦に保つかどうかを取得または設定します。<br/>            読み取り/書き込み **bool**。 |
| [`slide`](/slides/python-net/ja/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/ja/aspose.slides/textframeformat/text_style/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ja/aspose.slides/textframeformat/get_effective/#) | 継承が適用された有効なテキストフレームの書式設定データを取得します。 |

### 参照
* クラス [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)
* クラス [`TextFrameFormat`](/slides/python-net/ja/aspose.slides/textframeformat)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)