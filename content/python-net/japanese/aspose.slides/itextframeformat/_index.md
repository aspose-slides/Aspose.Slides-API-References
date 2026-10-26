---
title: ITextFrameFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/itextframeformat/
---
## ITextFrameFormat クラス

TextFrame の書式プロパティを含みます。

ITextFrameFormat 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`text_style`](/slides/python-net/ja/aspose.slides/itextframeformat/text_style/) | テキストのスタイルを返します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/ja/aspose.slides/itextframeformat/margin_left/) | TextFrame の左余白（ポイント）を取得または設定します。<br/>            読み書き **float**. |
| [`margin_right`](/slides/python-net/ja/aspose.slides/itextframeformat/margin_right/) | TextFrame の右余白（ポイント）を取得または設定します。<br/>            読み書き **float**. |
| [`margin_top`](/slides/python-net/ja/aspose.slides/itextframeformat/margin_top/) | TextFrame の上余白（ポイント）を取得または設定します。<br/>            読み書き **float**. |
| [`margin_bottom`](/slides/python-net/ja/aspose.slides/itextframeformat/margin_bottom/) | TextFrame の下余白（ポイント）を取得または設定します。<br/>            読み書き **float**. |
| [`wrap_text`](/slides/python-net/ja/aspose.slides/itextframeformat/wrap_text/) | テキストが TextFrame の余白で折り返される場合は **True**。<br/>            読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/ja/aspose.slides/itextframeformat/anchoring_type/) | 垂直方向のアンカーテキストを取得または設定します。<br/>            読み書き [`TextAnchorType`](/slides/python-net/ja/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/ja/aspose.slides/itextframeformat/center_text/) | NullableBool.True の場合、テキストはボックス内で横方向に中央揃えされます。<br/>            読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/ja/aspose.slides/itextframeformat/text_vertical_type/) | テキストの向きを決定します。<br/>            このプロパティとカスタム角度（RotationAngle プロパティ）から取得された視覚的テキスト回転の合計値です。<br/>            読み書き [`TextVerticalType`](/slides/python-net/ja/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/ja/aspose.slides/itextframeformat/autofit_type/) | テキストの自動調整モードを取得または設定します。<br/>            読み書き [`TextAutofitType`](/slides/python-net/ja/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/ja/aspose.slides/itextframeformat/column_count/) | テキスト領域の列数を取得または設定します。<br/>            この値は正の数である必要があります。そうでない場合、値は 0 に設定されます。<br/>            値 0 は未定義の値を意味します。<br/>            読み書き **int**. |
| [`column_spacing`](/slides/python-net/ja/aspose.slides/itextframeformat/column_spacing/) | テキスト領域の列間のスペース（ポイント）を取得または設定します。これは列が 1 つ以上ある場合にのみ適用されます。<br/>            この値は正の数である必要があります。そうでない場合、値は 0 に設定されます。<br/>            読み書き **float**. |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/itextframeformat/three_d_format/) | テキストの 3D 効果プロパティを表す ThreeDFormat オブジェクトを返します。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/ja/aspose.slides/itextframeformat/keep_text_flat/) | テキストを 3D シーンから完全に除外するかどうかを取得または設定します。<br/>            読み書き **bool**. |
| [`rotation_angle`](/slides/python-net/ja/aspose.slides/itextframeformat/rotation_angle/) | バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合、付随するシェイプの回転が使用されます。指定されている場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されている上で、テキスト自体にも回転が適用されることがあります。<br/>            このプロパティと事前定義された垂直タイプ（TextVerticalType プロパティ）から取得された視覚的テキスト回転の合計値です。<br/>            読み書き **float**. |
| [`transform`](/slides/python-net/ja/aspose.slides/itextframeformat/transform/) | テキスト折り返しシェイプを取得または設定します。<br/>            読み書き [`TextShapeType`](/slides/python-net/ja/aspose.slides/textshapetype). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ja/aspose.slides/itextframeformat/get_effective/#) | 継承が適用された有効なテキストフレーム書式データを取得します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)