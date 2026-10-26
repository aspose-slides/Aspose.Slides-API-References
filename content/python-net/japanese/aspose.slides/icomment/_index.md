---
title: IComment class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icomment/
---
## IComment クラス

スライド上のコメントを表します。

IComment 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`text`](/slides/python-net/ja/aspose.slides/icomment/text/) | スライドコメントのプレーンテキストを取得または設定します。<br/>            Read/write **str**. |
| [`created_time`](/slides/python-net/ja/aspose.slides/icomment/created_time/) | コメント作成時刻を取得または設定します。<br/>            このプロパティに **System.DateTime** を設定すると、コメント時刻が設定されていないことを意味します。<br/>            Read/write **System.DateTime**. |
| [`slide`](/slides/python-net/ja/aspose.slides/icomment/slide/) | コメントの親スライドを取得または設定します。<br/>            読み取り専用 [`ISlide`](/slides/python-net/ja/aspose.slides/islide). |
| [`author`](/slides/python-net/ja/aspose.slides/icomment/author/) | コメントの作者を取得します。<br/>            読み取り専用 [`ICommentAuthor`](/slides/python-net/ja/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/ja/aspose.slides/icomment/position/) | スライド上のコメントの位置を取得または設定します。<br/>            Read/write [`PointF`](/slides/python-net/ja/aspose.slides/pointf). |
| [`parent_comment`](/slides/python-net/ja/aspose.slides/icomment/parent_comment/) | 親コメントを取得または設定します。<br/>            Read/write [`IComment`](/slides/python-net/ja/aspose.slides/icomment). |

## メソッド

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides/icomment/remove/#) | コメントとそのすべての返信を親コレクションから削除します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)