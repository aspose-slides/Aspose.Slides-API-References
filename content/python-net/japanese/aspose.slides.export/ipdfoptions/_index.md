---
title: IPdfOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ipdfoptions/
---
## IPdfOptions クラス

Provides options that control how a presentation is saved in Pdf format.

The IPdfOptions type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`text_compression`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/text_compression/) | ドキュメント内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。<br/>            読み取り/書き込み [`PdfTextCompression`](/slides/python-net/ja/aspose.slides.export/pdftextcompression)。 |
| [`best_images_compression_ratio`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | 各画像に対して、デフォルトの代わりに最も効果的な圧縮を自動的に選択するかどうかを示します。<br/>            **bool**.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。<br/>            最適な画像圧縮率の選択は計算コストが高く、追加の RAM を消費します。このオプションはデフォルトで **bool**.false です。 |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | true の場合、ASCII 文字 32-127 の TrueType フォントを埋め込みます。<br/>            文字コード 127 より大きいフォントは常に埋め込まれます。<br/>            読み取り/書き込み **bool**。 |
| [`show_hidden_slides`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/show_hidden_slides/) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`additional_common_font_families`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Aspose.Slides が共通と見なすフォント ファミリーのユーザー定義名の配列を取得または設定します。<br/>            読み取り/書き込み **str**[]. |
| [`embed_full_fonts`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/embed_full_fonts/) | フォントのすべての文字を埋め込むか、使用したサブセットのみを埋め込むかを決定します。<br/>            読み取り/書き込み **bool**。 |
| [`rasterize_unsupported_font_styles`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | フォントが太字スタイルに対応していない場合、テキストをビットマップとしてラスタライズし PDF に保存するかどうかを示します。<br/>            このアプローチは特定のフォントに対して、結果の PDF のテキスト品質を向上させる可能性があります。<br/>            読み取り/書き込み **bool**。 |
| [`jpeg_quality`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/jpeg_quality/) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`compliance`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/compliance/) | 生成された PDF ドキュメントの望ましい適合レベルを指定します。<br/>            読み取り/書き込み [`PdfCompliance`](/slides/python-net/ja/aspose.slides.export/pdfcompliance)。 |
| [`password`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/password/) | PDF ドキュメントを保護するためのユーザー パスワードを設定します。<br/>            読み取り/書き込み **str**。 |
| [`access_permissions`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/access_permissions/) | ドキュメントがユーザー アクセスで開かれたときに付与すべきアクセス許可を指定するフラグのセットを含みます。<br/>            [`PdfAccessPermissions`](/slides/python-net/ja/aspose.slides.export/pdfaccesspermissions) を参照してください。 |
| [`save_metafiles_as_png`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | true の場合、プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。<br/>            読み取り/書き込み **bool**。 |
| [`sufficient_resolution`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/sufficient_resolution/) | PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。<br/>            <br/>このプロパティはファイル サイズ、エクスポート時間、画像品質に影響します。<br/><br/><br/>デフォルト値は **96** です。<br/><br/><br/>            読み取り/書き込み **float**。 |
| [`draw_slides_frame`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/draw_slides_frame/) | true の場合、各スライドの周囲に黒いフレームを描画します。<br/>            読み取り/書き込み **bool**。 |
| [`slides_layout_options`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/slides_layout_options/) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [`ISlidesLayoutOptions`](/slides/python-net/ja/aspose.slides.export/islideslayoutoptions)。 |
| [`image_transparent_color`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/image_transparent_color/) | 画像の透過色を取得または設定します。 |
| [`apply_image_transparent`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/apply_image_transparent/) | `true` の場合、指定された透過色を画像に適用します。 |
| [`ink_options`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/ink_options/) | エクスポートされたドキュメント内のインク オブジェクトの外観を制御するオプションを提供します。<br/>            読み取り専用 [`IInkOptions`](/slides/python-net/ja/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/include_ole_data/) | true の場合、プレゼンテーションからすべての OLE データを変換し、結果の PDF に埋め込みファイルとして保存します。<br/>            読み取り/書き込み **bool**。 |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### 参照
* module [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)