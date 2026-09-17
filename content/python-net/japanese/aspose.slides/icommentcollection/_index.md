---
title: ICommentCollection class
second_title: .NET 経由の Python 用 Aspose.Slides API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icommentcollection/
---
## ICommentCollection クラス

1 人の作成者のコメントのコレクションを表します。

ICommentCollection 型は以下のメンバーを公開します。

指定されたインデックスの要素を取得します。
            読み取り専用 [`IComment`](/slides/python-net/ja/aspose.slides/icomment)。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/icommentcollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`to_array(self)`](/slides/python-net/ja/aspose.slides/icommentcollection/to_array/#) | すべてのコメントを含む配列を作成して返します。 |
| [`to_array(self, start_index, count)`](/slides/python-net/ja/aspose.slides/icommentcollection/to_array/#int-int) | 指定された範囲のすべてのコメントを含む配列を作成して返します。 |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/ja/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | コレクションの末尾に新しいコメントを追加します。 |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/ja/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | コレクションの末尾に新しいモダンコメントを追加します。 |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/ja/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | 指定されたインデックスに新しいコメントを挿入します。 |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/ja/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | 指定されたインデックスに新しいモダンコメントを挿入します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/icommentcollection/remove_at/#int) | コレクション内の指定されたインデックスの要素を削除します。 |
| [`remove(self, comment)`](/slides/python-net/ja/aspose.slides/icommentcollection/remove/#icomment) | コレクション内の指定されたコメントの最初の出現を削除します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides/icommentcollection/clear/#) | コレクションからすべてのコメントを削除します。 |

### 参照
* クラス [`IComment`](/slides/python-net/ja/aspose.slides/icomment)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)