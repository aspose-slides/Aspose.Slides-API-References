---
title: IParagraphCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iparagraphcollection/
---
## IParagraphCollection クラス

段落のコレクションを表します。

IParagraphCollection 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`count`](/slides/python-net/ja/aspose.slides/iparagraphcollection/count/) | コレクションに実際に含まれる要素数を取得します。<br/>            読み取り専用 **int**. |
| [`slide`](/slides/python-net/ja/aspose.slides/iparagraphcollection/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/iparagraphcollection/presentation/) |  |

指定されたインデックスの要素を取得します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/iparagraphcollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add(self, value)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/add/#iparagraph) | Paragraph をコレクションの末尾に追加します。 |
| [`add(self, value)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/add/#iparagraphcollection) | ParagraphCollection の内容をコレクションの末尾に追加します。 |
| [`insert(self, index, value)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/insert/#int-iparagraph) | 指定されたインデックスに Paragraph をコレクションへ挿入します。 |
| [`insert(self, index, value)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/insert/#int-iparagraphcollection) | 指定されたインデックスに ParagraphCollection の内容をコレクションへ挿入します。 |
| [`add_from_html(self, text)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/add_from_html/#str) | 指定された HTML 文字列からテキストをコレクションに追加します。 |
| [`add_from_html(self, text, resolver, uri)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | 指定された HTML 文字列からテキストをコレクションに追加します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/clear/#) | コレクションからすべての要素を削除します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/remove_at/#int) | コレクションの指定されたインデックスにある要素を削除します。 |
| [`remove(self, item)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/remove/#iparagraph) | 特定の段落の最初の出現を削除します。 |
| [`export_to_html(self, first_paragraph_index, paragraphs_count, options)`](/slides/python-net/ja/aspose.slides/iparagraphcollection/export_to_html/#int-int-asposeslidesexportitexttohtmlconversionoptions) | 指定された段落を HTML に変換し、String オブジェクトとして返します。 |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)