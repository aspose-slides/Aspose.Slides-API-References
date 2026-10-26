---
title: PdfOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/pdfoptions/
---
## PdfOptions クラス

プレゼンテーションが Pdf 形式で保存される方法を制御するオプションを提供します。

**継承:**[`PdfOptions`](/slides/python-net/ja/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

PdfOptions 型は次のメンバーを公開します。

## コンストラクター

| コンストラクター | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/pdfoptions/__init__/#) | デフォルトコンストラクター。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/pdfoptions/warning_callback/) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み書き [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/pdfoptions/progress_callback/) | 保存進捗率の更新を受け取るコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/pdfoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み書き **str**. |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/pdfoptions/gradient_style/) | グラデーションの視覚スタイルを取得または設定します。<br/>            読み書き [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/pdfoptions/skip_java_script_links/) | プレゼンテーションを保存する際に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。<br/>            読み書き **bool**. デフォルト値は **false** です。 |
| [`slides_layout_options`](/slides/python-net/ja/aspose.slides.export/pdfoptions/slides_layout_options/) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [`ISlidesLayoutOptions`](/slides/python-net/ja/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/ja/aspose.slides.export/pdfoptions/ink_options/) | エクスポートされたドキュメントの Ink オブジェクトの外観を制御するオプションを提供します。<br/>            読み取り専用 [`IInkOptions`](/slides/python-net/ja/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ja/aspose.slides.export/pdfoptions/show_hidden_slides/) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`text_compression`](/slides/python-net/ja/aspose.slides.export/pdfoptions/text_compression/) | ドキュメント内のすべてのテキストコンテンツに使用される圧縮タイプを指定します。<br/>            読み書き [`PdfTextCompression`](/slides/python-net/ja/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/ja/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | 各画像に対して最も効果的な圧縮（デフォルトのものではなく）を自動的に選択するかどうかを示します。<br/>            **bool**.true に設定すると、プレゼンテーション内のすべての画像について最適な圧縮アルゴリズムが選択され、結果として PDF ドキュメントのサイズが小さくなります。<br/>            最適な画像圧縮率の選択は計算コストが高く、追加の RAM が必要となり、このオプションのデフォルトは **bool**.false です。 |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/ja/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | ASCII (33..127 のコード範囲) テキストに対して、Aspose.Slides が共通フォントを埋め込むかどうかを決定します。<br/>            127 より大きい文字コードのフォントは常に埋め込まれます。<br/>            共通フォントリストには PDF の基本 14 フォントとユーザーが指定した追加フォントが含まれます。<br/>            読み書き **bool**. |
| [`additional_common_font_families`](/slides/python-net/ja/aspose.slides.export/pdfoptions/additional_common_font_families/) | Aspose.Slides が共通とみなすフォントファミリのユーザー定義名の配列を取得または設定します。<br/>            読み書き **str**[]. |
| [`embed_full_fonts`](/slides/python-net/ja/aspose.slides.export/pdfoptions/embed_full_fonts/) | フォントのすべての文字を埋め込むか、使用されたサブセットだけを埋め込むかを決定します。<br/>            読み書き **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/ja/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | フォントが太字スタイルに対応していない場合に、テキストをビットマップとしてラスタライズし PDF に保存するかどうかを示します。<br/>            このアプローチは特定のフォントで結果の PDF のテキスト品質を向上させる可能性があります。<br/>            読み書き **bool**. |
| [`jpeg_quality`](/slides/python-net/ja/aspose.slides.export/pdfoptions/jpeg_quality/) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。<br/>            読み書き **int**. |
| [`compliance`](/slides/python-net/ja/aspose.slides.export/pdfoptions/compliance/) | 生成された PDF ドキュメントの目的とするコンフォーマンスレベル。<br/>            読み書き [`PdfCompliance`](/slides/python-net/ja/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/ja/aspose.slides.export/pdfoptions/password/) | PDF ドキュメントを保護するためのユーザーパスワードを設定します。<br/>            読み書き **str**. |
| [`access_permissions`](/slides/python-net/ja/aspose.slides.export/pdfoptions/access_permissions/) | ドキュメントがユーザーアクセスで開かれた際に付与されるアクセス許可を指定するフラグのセットを含みます<br/>            参照 [`PdfAccessPermissions`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/ja/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true に設定します。<br/>            読み書き **bool**. |
| [`sufficient_resolution`](/slides/python-net/ja/aspose.slides.export/pdfoptions/sufficient_resolution/) | PDF ドキュメント内の画像解像度を決定する値を取得または設定します。<br/>            <br/>このプロパティはファイルサイズ、エクスポート時間、画像品質に影響します。<br/><br/><br/>デフォルト値は **96** です。<br/><br/><br/>            読み書き **float**. |
| [`draw_slides_frame`](/slides/python-net/ja/aspose.slides.export/pdfoptions/draw_slides_frame/) | 各スライドの周りに黒い枠を描画する場合は true に設定します。<br/>            読み書き **bool**. |
| [`image_transparent_color`](/slides/python-net/ja/aspose.slides.export/pdfoptions/image_transparent_color/) | 画像の透過色を取得または設定します。 |
| [`apply_image_transparent`](/slides/python-net/ja/aspose.slides.export/pdfoptions/apply_image_transparent/) | `true` の場合、指定された透過色を画像に適用します。 |
| [`include_ole_data`](/slides/python-net/ja/aspose.slides.export/pdfoptions/include_ole_data/) | プレゼンテーションのすべての OLE データを結果の PDF に埋め込みファイルとして変換する場合は true に設定します。<br/>            読み書き **bool**. |

### 参照
* クラス [`PdfOptions`](/slides/python-net/ja/aspose.slides.export/pdfoptions)
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)