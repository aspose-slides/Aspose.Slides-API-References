---
title: Comment class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/comment/
---
## Comment クラス

スライド上のコメントを表します。

Comment 型は以下のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`text`](/slides/python-net/ja/aspose.slides/comment/text/) | スライドコメントのプレーンテキストを取得または設定します。<br/>            読み取り/書き込み **str**. |
| [`created_time`](/slides/python-net/ja/aspose.slides/comment/created_time/) | コメント作成時刻を取得または設定します。<br/>            このプロパティを **System.DateTime** に設定すると、コメント時刻が設定されていないことを意味します。<br/>            読み取り/書き込み **System.DateTime**. |
| [`slide`](/slides/python-net/ja/aspose.slides/comment/slide/) | コメントの親スライドを取得または設定します。<br/>            読み取り専用 [`ISlide`](/slides/python-net/ja/aspose.slides/islide). |
| [`author`](/slides/python-net/ja/aspose.slides/comment/author/) | コメントの作成者を取得します。<br/>            読み取り専用 [`ICommentAuthor`](/slides/python-net/ja/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/ja/aspose.slides/comment/position/) | スライド上のコメントの位置を取得または設定します。<br/>            読み取り/書き込み **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/ja/aspose.slides/comment/parent_comment/) | 親コメントを取得または設定します。<br/>            読み取り/書き込み [`IComment`](/slides/python-net/ja/aspose.slides/icomment). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides/comment/remove/#) | コメントとそのすべての返信を親コレクションから削除します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)