---
title: ModernComment class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/moderncomment/
---
## ModernComment クラス

スライド上のコメントを表します。

**継承:**[`ModernComment`](/slides/python-net/ja/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/ja/aspose.slides/comment)

ModernComment 型は以下のメンバーを公開します：

## プロパティ

| Property | Description |
| :- | :- |
| [`text`](/slides/python-net/ja/aspose.slides/moderncomment/text/) | スライドコメントのプレーンテキストを取得または設定します。<br/>            読み書き **str**. |
| [`created_time`](/slides/python-net/ja/aspose.slides/moderncomment/created_time/) | コメント作成時刻を取得または設定します。<br/>            このプロパティに **System.DateTime** を設定すると、コメント時刻が設定されません。<br/>            読み書き **System.DateTime**. |
| [`slide`](/slides/python-net/ja/aspose.slides/moderncomment/slide/) | コメントの親スライドを取得または設定します。<br/>            読み取り専用 [`ISlide`](/slides/python-net/ja/aspose.slides/islide). |
| [`author`](/slides/python-net/ja/aspose.slides/moderncomment/author/) | コメントの作成者を取得します。<br/>            読み取り専用 [`ICommentAuthor`](/slides/python-net/ja/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/ja/aspose.slides/moderncomment/position/) | スライド上のコメントの位置を取得または設定します。<br/>            読み書き **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/ja/aspose.slides/moderncomment/parent_comment/) | 親コメントを取得または設定します。<br/>            読み書き [`IComment`](/slides/python-net/ja/aspose.slides/icomment). |
| [`shape`](/slides/python-net/ja/aspose.slides/moderncomment/shape/) | コメントに関連付けられたシェイプを取得します。<br/>            読み取り専用 [`IShape`](/slides/python-net/ja/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/ja/aspose.slides/moderncomment/text_selection_start/) | コメントが AutoShape に関連付いている場合、テキストフレーム内のテキスト選択開始位置を取得または設定します。<br/>            読み書き **int**. |
| [`text_selection_length`](/slides/python-net/ja/aspose.slides/moderncomment/text_selection_length/) | コメントが AutoShape に関連付いている場合、テキストフレーム内のテキスト選択長さを取得または設定します。<br/>            読み書き **int**. |
| [`status`](/slides/python-net/ja/aspose.slides/moderncomment/status/) | コメントのステータスを取得または設定します。<br/>            読み書き [`ModernCommentStatus`](/slides/python-net/ja/aspose.slides/moderncommentstatus). |

## メソッド

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides/moderncomment/remove/#) | コメントとそのすべての返信を親コレクションから削除します。 |

### 参照
* クラス [`Comment`](/slides/python-net/ja/aspose.slides/comment)
* クラス [`ModernComment`](/slides/python-net/ja/aspose.slides/moderncomment)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)