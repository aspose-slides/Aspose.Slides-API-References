---
title: ISlideCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/islidecollection/
---
## ISlideCollection クラス

スライドのコレクションを表します。

ISlideCollection 型は次のメンバーを公開します。

指定されたインデックスの要素を取得します。 読み取り専用 [`ISlide`](/slides/python-net/ja/aspose.slides/islide)。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/islidecollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/ja/aspose.slides/islidecollection/add_clone/#islide) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [`add_clone(self, source_slide, section)`](/slides/python-net/ja/aspose.slides/islidecollection/add_clone/#islide-isection) | 指定されたスライドのコピーを、指定されたセクションの末尾に追加します。 |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/ja/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ja/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | 指定された元スライドのコピーをコレクションの末尾に追加します。<br/>            適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトとは、元スライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、<br/>            元スライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。 |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_clone/#int-islide) | 指定された位置に、指定されたスライドのコピーをコレクションに挿入します。 |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | 指定された位置に、指定されたスライドのコピーをコレクションに挿入します。 |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | 指定された位置に、指定された元スライドのコピーをコレクションに挿入します。<br/>            適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトとは、元スライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、<br/>            元スライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。 |
| [`to_array(self)`](/slides/python-net/ja/aspose.slides/islidecollection/to_array/#) | すべてのスライドを含む配列を作成し、返します。 |
| [`to_array(self, start_index, count)`](/slides/python-net/ja/aspose.slides/islidecollection/to_array/#int-int) | 指定された範囲のすべてのスライドを含む配列を作成し、返します。 |
| [`reorder(self, index, slide)`](/slides/python-net/ja/aspose.slides/islidecollection/reorder/#int-islide) | コレクション内のスライドを指定された位置に移動します。 |
| [`reorder(self, index, slides)`](/slides/python-net/ja/aspose.slides/islidecollection/reorder/#int-listislide) | コレクション内のスライドを指定された位置に移動します。<br/>            スライドはインデックスから開始し、リストに現れる順序で配置されます。 |
| [`add_from_pdf(self, path)`](/slides/python-net/ja/aspose.slides/islidecollection/add_from_pdf/#str) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/ja/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | PDF インポートオプションを考慮して、PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/ja/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/ja/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/ja/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [`add_from_html(self, html_text)`](/slides/python-net/ja/aspose.slides/islidecollection/add_from_html/#str) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/ja/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [`add_from_html(self, html_stream)`](/slides/python-net/ja/aspose.slides/islidecollection/add_from_html/#iorawiobase) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。 |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_from_html/#int-str) | HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。 |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。 |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。 |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。 |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。 |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。 |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。 |
| [`add_empty_slide(self, layout)`](/slides/python-net/ja/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | 新しい空のスライドをコレクションの末尾に追加します。 |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/ja/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | 指定された位置に、指定されたスライドのコピーをコレクションに挿入します。 |
| [`remove(self, value)`](/slides/python-net/ja/aspose.slides/islidecollection/remove/#islide) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/islidecollection/remove_at/#int) | コレクションの指定されたインデックスの要素を削除します。 |
| [`index_of(self, slide)`](/slides/python-net/ja/aspose.slides/islidecollection/index_of/#islide) | コレクション内の指定されたスライドのインデックスを返します。 |

### 参照
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)