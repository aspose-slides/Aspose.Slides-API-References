---
title: AudioFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/audioframe/
---
## AudioFrame クラス

スライド上の音声クリップを表します。

**Inheritance:**[`AudioFrame`](/slides/python-net/ja/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

AudioFrame タイプは以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/audioframe/is_text_holder/) | シェイプが TextHolder_PPT かどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/audioframe/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/audioframe/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/audioframe/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み取り/書き込み [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/audioframe/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み取り/書き込み [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/audioframe/line_format/) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/audioframe/three_d_format/) | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/audioframe/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/audioframe/fill_format/) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/audioframe/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み取り/書き込み [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/audioframe/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み取り/書き込み [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/audioframe/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/audioframe/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み取り/書き込み **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/audioframe/z_order_position/) | シェイプの Z 順序での位置を返します。<br/>            Shapes[0] は Z 順序の背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/audioframe/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/audioframe/rotation/) | 指定されたシェイプが Z 軸周りに回転している度数を取得または設定します。正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。<br/>            読み取り/書き込み **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/audioframe/x/) | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/audioframe/y/) | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/audioframe/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/audioframe/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/audioframe/black_white_mode/) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。<br/>            読み取り/書き込み [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/audioframe/unique_id/) | アドインやその他のコードで使用することを意図した、プレゼンテーション内スコープの内部識別子を返します。<br/>            この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/audioframe/office_interop_shape_id/) | スライドスコープの一意識別子を返します。この識別子はシェイプの存続期間中は一定であり、PowerPoint やインタープコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/audioframe/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/audioframe/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/audioframe/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み取り/書き込み **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/audioframe/is_decorative/) | '装飾としてマーク' オプションを取得または設定します。<br/>            読み取り/書き込み **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/audioframe/shape_lock/) | シェイプのロック情報を返します。<br/>            読み取り専用 [`IPictureFrameLock`](/slides/python-net/ja/aspose.slides/ipictureframelock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/audioframe/is_grouped/) | シェイプがグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/audioframe/parent_group/) | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返します。そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/audioframe/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/audioframe/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`shape_style`](/slides/python-net/ja/aspose.slides/audioframe/shape_style/) | シェイプのスタイルオブジェクトを返します。<br/>            読み取り専用 [`IShapeStyle`](/slides/python-net/ja/aspose.slides/ishapestyle)。 |
| [`shape_type`](/slides/python-net/ja/aspose.slides/audioframe/shape_type/) | PictureFrame の AutoShape タイプを取得または設定します。<br/>            設定可能な項目は集合 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) のすべてですが、以下のすべての線種は除外されます:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            読み取り/書き込み [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| [`adjustments`](/slides/python-net/ja/aspose.slides/audioframe/adjustments/) | シェイプの調整値のコレクションを返します。<br/>            読み取り専用 [`IAdjustValueCollection`](/slides/python-net/ja/aspose.slides/iadjustvaluecollection)。 |
| [`picture_frame_lock`](/slides/python-net/ja/aspose.slides/audioframe/picture_frame_lock/) | シェイプのロック情報を返します。<br/>            読み取り専用 [`IPictureFrameLock`](/slides/python-net/ja/aspose.slides/ipictureframelock)。 |
| [`picture_format`](/slides/python-net/ja/aspose.slides/audioframe/picture_format/) | 画像フレームの PictureFillFormat オブジェクトを返します。<br/>            読み取り専用 [`IPictureFillFormat`](/slides/python-net/ja/aspose.slides/ipicturefillformat)。 |
| [`relative_scale_height`](/slides/python-net/ja/aspose.slides/audioframe/relative_scale_height/) | 画像フレームの高さ（元の画像サイズに対する相対）スケールを取得または設定します。値 1.0 は 100% に相当します。<br/>            読み取り/書き込み **float**。 |
| [`relative_scale_width`](/slides/python-net/ja/aspose.slides/audioframe/relative_scale_width/) | 画像フレームの幅（元の画像サイズに対する相対）スケールを取得または設定します。値 1.0 は 100% に相当します。<br/>            読み取り/書き込み **float**。 |
| [`is_cameo`](/slides/python-net/ja/aspose.slides/audioframe/is_cameo/) | PictureFrame が Cameo オブジェクトかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`audio_cd_start_track`](/slides/python-net/ja/aspose.slides/audioframe/audio_cd_start_track/) | 開始トラックインデックスを取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`audio_cd_start_track_time`](/slides/python-net/ja/aspose.slides/audioframe/audio_cd_start_track_time/) | 開始トラック時間を取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`audio_cd_end_track`](/slides/python-net/ja/aspose.slides/audioframe/audio_cd_end_track/) | 終了トラックインデックスを取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`audio_cd_end_track_time`](/slides/python-net/ja/aspose.slides/audioframe/audio_cd_end_track_time/) | 終了トラック時間を取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`volume`](/slides/python-net/ja/aspose.slides/audioframe/volume/) | 音声のボリュームを取得または設定します。<br/>            読み取り/書き込み [`AudioVolumeMode`](/slides/python-net/ja/aspose.slides/audiovolumemode)。 |
| [`play_mode`](/slides/python-net/ja/aspose.slides/audioframe/play_mode/) | 音声の再生モードを取得または設定します。<br/>            読み取り/書き込み [`AudioPlayModePreset`](/slides/python-net/ja/aspose.slides/audioplaymodepreset)。 |
| [`hide_at_showing`](/slides/python-net/ja/aspose.slides/audioframe/hide_at_showing/) | AudioFrame が非表示かどうかを判断します。<br/>            読み取り/書き込み **bool**。 |
| [`play_loop_mode`](/slides/python-net/ja/aspose.slides/audioframe/play_loop_mode/) | 音声がループ再生されるかどうかを判断します。<br/>            読み取り/書き込み **bool**。 |
| [`play_across_slides`](/slides/python-net/ja/aspose.slides/audioframe/play_across_slides/) | 音声がスライド全体で再生されるかどうかを判断します。<br/>            読み取り/書き込み **bool**。 |
| [`rewind_audio`](/slides/python-net/ja/aspose.slides/audioframe/rewind_audio/) | 音声が再生後に自動的に開始位置に巻き戻されるかどうかを判断します。<br/>            読み取り/書き込み **bool**。 |
| [`embedded`](/slides/python-net/ja/aspose.slides/audioframe/embedded/) | サウンドがプレゼンテーションに埋め込まれているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`link_path_long`](/slides/python-net/ja/aspose.slides/audioframe/link_path_long/) | AudioFrame にリンクされた音声ファイルの名前を取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`embedded_audio`](/slides/python-net/ja/aspose.slides/audioframe/embedded_audio/) | 埋め込み音声オブジェクトを取得または設定します。<br/>            読み取り/書き込み [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)。 |
| [`fade_in_duration`](/slides/python-net/ja/aspose.slides/audioframe/fade_in_duration/) | メディアの初期フェードインの時間（ミリ秒）を指定します。<br/>            読み取り/書き込み **float**。 |
| [`fade_out_duration`](/slides/python-net/ja/aspose.slides/audioframe/fade_out_duration/) | メディアの終了フェードアウトの時間（ミリ秒）を指定します。<br/>            読み取り/書き込み **float**。 |
| [`volume_value`](/slides/python-net/ja/aspose.slides/audioframe/volume_value/) | 音声のボリュームをパーセントで取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`trim_from_start`](/slides/python-net/ja/aspose.slides/audioframe/trim_from_start/) | 再生時にメディアの先頭から除去する時間（ミリ秒）を指定します。<br/>            読み取り/書き込み **float**。 |
| [`trim_from_end`](/slides/python-net/ja/aspose.slides/audioframe/trim_from_end/) | 再生時にメディアの末尾から除去する時間（ミリ秒）を指定します。<br/>            読み取り/書き込み **float**。 |
| [`caption_tracks`](/slides/python-net/ja/aspose.slides/audioframe/caption_tracks/) | 音声フレームに関連付けられたクローズドキャプションのコレクションを取得します。<br/>            このプロパティは読み取り専用で、すべてのキャプショントラックを含む [`ICaptionsCollection`](/slides/python-net/ja/aspose.slides/icaptionscollection) を返します。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/audioframe/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/audioframe/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/audioframe/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/audioframe/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/audioframe/get_base_placeholder/#) | 基本的なプレースホルダーシェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）を返します。<br/>            継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/audioframe/get_visual_bounds/#) | シェイプのレンダリングされたコンテンツから計算された視覚的境界を取得します。 |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/audioframe/get_geometry_paths/#) | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準とした相対座標です。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトからシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とした相対座標でなければなりません。<br/>             シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) の配列からシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とした相対座標でなければなりません。<br/>             シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/audioframe/create_shape_elements/#) | シェイプの要素の配列を作成して返します。 |

### 参照
* クラス [`AudioFrame`](/slides/python-net/ja/aspose.slides/audioframe)
* クラス [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape)
* クラス [`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)