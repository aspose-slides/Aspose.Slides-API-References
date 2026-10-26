---
title: SlideUtil class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.util/slideutil/
---
## SlideUtil クラス

プレゼンテーション内のシェイプとテキストの検索を支援するメソッドを提供します。

SlideUtil 型は次のメンバーを公開します。

## メソッド

| Method | Description |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/ja/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | PPTX プレゼンテーション内で代替テキストに基づいてシェイプを検索します。 |
| [`find_shape(slide, alt_text)`](/slides/python-net/ja/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | PPTX プレゼンテーションのスライド上で代替テキストに基づいてシェイプを検索します。 |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/ja/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | スライド上のすべてのシェイプの配置を変更します。シェイプを余白またはスライドの端に揃えます<br/>            または相互に相対的に揃えます。 |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/ja/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | スライド上の選択されたシェイプの配置を変更します。シェイプを余白またはスライドの端に揃えます<br/>            または相互に相対的に揃えます。 |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/ja/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | グループシェイプ内のすべてのシェイプの配置を変更します。シェイプを余白またはスライドの端に揃えます<br/>            または相互に相対的に揃えます。 |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/ja/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | グループシェイプ内の選択されたシェイプの配置を変更します。シェイプを余白またはスライドの端に揃えます<br/>            または相互に相対的に揃えます。 |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/ja/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | 指定されたスライド上で、指定されたプレースホルダータイプに一致するすべてのシェイプを検索します。 |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/ja/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | プレゼンテーション内のテキストを検索し、指定された形式で置換します。 |
| [`get_all_text_boxes(slide)`](/slides/python-net/ja/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | PPTX プレゼンテーションのスライド上のすべてのテキストフレームを返します。 |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/ja/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | 指定されたスライド上で、指定されたテキストを含むすべてのテキストフレームを返します。 |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/ja/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | PPTX プレゼンテーション内のすべてのテキストフレームを返します。 |
| [`to_save_format(format)`](/slides/python-net/ja/aspose.slides.util/slideutil/to_save_format/#sourceformat) | ソースファイル形式を対応する [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) に変換します。 |

### 参照
* モジュール [`aspose.slides.util`](/slides/python-net/ja/aspose.slides.util)
* ライブラリ [`Aspose.Slides`](/slides/python-net)