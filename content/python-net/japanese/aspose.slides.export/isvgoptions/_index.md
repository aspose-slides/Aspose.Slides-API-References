---
title: ISVGOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/isvgoptions/
---
## ISVGOptions クラス

SVG オプションを表します。

ISVGOptions 型は以下のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/ja/aspose.slides.export/isvgoptions/vectorize_text/) | スライド上のテキストをグラフィックとして保存するかどうかを決定します。<br/>            読み書き **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/ja/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | メタファイルのラスター化に対する下限解像度を取得または設定します。<br/>            読み書き **int**. |
| [`disable_3d_text`](/slides/python-net/ja/aspose.slides.export/isvgoptions/disable_3d_text/) | SVG で 3D テキストが無効かどうかを決定します。<br/>            読み書き **bool**. |
| [`disable_gradient_split`](/slides/python-net/ja/aspose.slides.export/isvgoptions/disable_gradient_split/) | FromCornerX と FromCenter グラデーションの分割を無効にします。<br/>            読み書き **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/ja/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 ではマーカーのインセットを定義する機能がありません。<br/>            Aspose.Slides の SVG 書き込みエンジンはこの問題に対する回避策を持っています：<br/>            矢印付きの線の端を切り取ることで、線がマーカーと重ならないようにします。<br/>            このオプションはその動作をオフにします。<br/>            読み書き **bool**. |
| [`jpeg_quality`](/slides/python-net/ja/aspose.slides.export/isvgoptions/jpeg_quality/) | JPEG エンコード品質を決定します。<br/>            読み書き **int**. |
| [`shape_formatting_controller`](/slides/python-net/ja/aspose.slides.export/isvgoptions/shape_formatting_controller/) | 形状変換を制御できるコールバックインターフェイスを取得および設定します。<br/>            読み書き [`ISvgShapeFormattingController`](/slides/python-net/ja/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/ja/aspose.slides.export/isvgoptions/pictures_compression/) | 画像の圧縮レベルを表します<br/>            読み書き [`ISVGOptions.pictures_compression`](/slides/python-net/ja/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/ja/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | トリミングされた部分が文書の一部として残るかどうかを示すブールフラグです。true の場合、トリミングされた<br/>            部分は削除され、false の場合は文書にシリアライズされます（これによりファイルが大きくなる可能性があります）<br/>            読み書き **bool**. |
| [`use_frame_size`](/slides/python-net/ja/aspose.slides.export/isvgoptions/use_frame_size/) | テキストフレームがレンダリング領域に含まれるかどうかを決定します。<br/>            読み書き **bool**。<br/>            デフォルト値は false です。 |
| [`use_frame_rotation`](/slides/python-net/ja/aspose.slides.export/isvgoptions/use_frame_rotation/) | レンダリング時に指定された形状の回転を実行するかどうかを決定します。<br/>            読み書き **bool**。<br/>            デフォルト値は true です。 |
| [`external_fonts_handling`](/slides/python-net/ja/aspose.slides.export/isvgoptions/external_fonts_handling/) | 外部から読み込まれたフォントの処理方法を決定します。<br/>            読み書き [`SvgExternalFontsHandling`](/slides/python-net/ja/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/ja/aspose.slides.export/isvgoptions/ink_options/) | エクスポートされた文書内の Ink オブジェクトの外観を制御するオプションを提供します。<br/>            読み取り専用 [`IInkOptions`](/slides/python-net/ja/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/ja/aspose.slides.export/isvgoptions/disable_font_ligatures/) | テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。<br/>            `true` に設定すると、レンダリング出力で合字が無効になります。デフォルトでは、このプロパティは `false` に設定されています。 |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### 関連項目
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)