---
title: ParagraphCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/paragraphcollection/
---
## ParagraphCollection クラス

段落のコレクションを表します。

The ParagraphCollection type exposes the following members:

## プロパティ

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/ja/aspose.slides/paragraphcollection/count/) | コレクションに実際に含まれる要素数を取得します。<br/>            読み取り専用 **int**. |
| [`is_read_only`](/slides/python-net/ja/aspose.slides/paragraphcollection/is_read_only/) | **System.Collections.Generic.ICollection`1** が読み取り専用かどうかを示す値を取得します。<br/>            読み取り専用 **bool**. |
| [`slide`](/slides/python-net/ja/aspose.slides/paragraphcollection/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/paragraphcollection/presentation/) |  |

指定されたインデックスの要素を取得します。

## インデクサ

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/paragraphcollection/__getitem__/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`add(self, value)`](/slides/python-net/ja/aspose.slides/paragraphcollection/add/#iparagraph) | Paragraph をコレクションの末尾に追加します。 |
| [`add(self, value)`](/slides/python-net/ja/aspose.slides/paragraphcollection/add/#iparagraphcollection) | ParagraphCollection の内容をコレクションの末尾に追加します。 |
| [`insert(self, index, value)`](/slides/python-net/ja/aspose.slides/paragraphcollection/insert/#int-iparagraph) | 指定されたインデックスに Paragraph をコレクションに挿入します。 |
| [`insert(self, index, value)`](/slides/python-net/ja/aspose.slides/paragraphcollection/insert/#int-iparagraphcollection) | 指定されたインデックスに ParagraphCollection の内容をコレクションに挿入します。 |
| [`add_from_html(self, text)`](/slides/python-net/ja/aspose.slides/paragraphcollection/add_from_html/#str) | 指定された HTML 文字列からテキストをコレクションに追加します。 |
| [`add_from_html(self, text, resolver, uri)`](/slides/python-net/ja/aspose.slides/paragraphcollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | 指定された HTML 文字列からテキストをコレクションに追加します。 |
| [`index_of(self, item)`](/slides/python-net/ja/aspose.slides/paragraphcollection/index_of/#iparagraph) | **System.Collections.Generic.IList`1** の特定の項目のインデックスを決定します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides/paragraphcollection/clear/#) | コレクションからすべての要素を削除します。 |
| [`contains(self, item)`](/slides/python-net/ja/aspose.slides/paragraphcollection/contains/#iparagraph) | **System.Collections.Generic.ICollection`1** が特定の値を含むかどうかを判定します。 |
| [`copy_to(self, array, array_index)`](/slides/python-net/ja/aspose.slides/paragraphcollection/copy_to/#listiparagraph-int) | **System.Collections.Generic.ICollection`1** の要素を **System.Array** にコピーします。特定の **System.Array** インデックスから開始します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/paragraphcollection/remove_at/#int) | コレクションの指定されたインデックスの要素を削除します。 |
| [`remove(self, item)`](/slides/python-net/ja/aspose.slides/paragraphcollection/remove/#iparagraph) | **System.Collections.Generic.ICollection`1** から特定のオブジェクトの最初の出現を削除します。 |
| [`export_to_html(self, first_paragraph_index, paragraphs_count, options)`](/slides/python-net/ja/aspose.slides/paragraphcollection/export_to_html/#int-int-asposeslidesexportitexttohtmlconversionoptions) | 指定された段落を HTML に変換し、String オブジェクトとして返します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)