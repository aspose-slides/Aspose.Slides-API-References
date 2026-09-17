---
title: CommentCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/commentcollection/
---
## CommentCollection クラス

1人の作者のコメントのコレクションを表します。

CommentCollection 型は以下のメンバーを公開します。

指定されたインデックスの要素を取得します。
読み取り専用 [`Comment`](/slides/python-net/ja/aspose.slides/comment)。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/commentcollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`to_array(self)`](/slides/python-net/ja/aspose.slides/commentcollection/to_array/#) | すべてのコメントを含む配列を作成して返します。 |
| [`to_array(self, start_index, count)`](/slides/python-net/ja/aspose.slides/commentcollection/to_array/#int-int) | 指定された範囲のコメントを含む配列を作成して返します。 |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/ja/aspose.slides/commentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | コレクションの末尾に新しいコメントを追加します。 |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/ja/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | コレクションの末尾に新しいモダンコメントを追加します。 |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/ja/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | 指定されたインデックスに新しいコメントを挿入します。 |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/ja/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | 指定されたインデックスに新しいモダンコメントを挿入します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/commentcollection/remove_at/#int) | コレクション内の指定されたインデックスの要素を削除します。 |
| [`remove(self, comment)`](/slides/python-net/ja/aspose.slides/commentcollection/remove/#icomment) | コレクション内の指定されたコメントの最初の出現を削除します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides/commentcollection/clear/#) | コレクションからすべてのコメントを削除します。 |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/ja/aspose.slides/commentcollection/find_comment_by_idx/#int) | インデックスでコレクション内のコメントを検索します。 |

### 参照
* クラス [`Comment`](/slides/python-net/ja/aspose.slides/comment)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)