---
title: ITextFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/itextframe/
---
## ITextFrame クラス

TextFrame を表します。

ITextFrame 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/ja/aspose.slides/itextframe/paragraphs/) | フレーム内のすべての段落のリストを返します。<br/>            読み取り専用 [`IParagraphCollection`](/slides/python-net/ja/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ja/aspose.slides/itextframe/text/) | TextFrame のプレーンテキストを取得または設定します。<br/>            読み書き **str**. |
| [`text_frame_format`](/slides/python-net/ja/aspose.slides/itextframe/text_frame_format/) | この TextFrame オブジェクトの書式設定オブジェクトを返します。<br/>            読み取り専用 [`ITextFrameFormat`](/slides/python-net/ja/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/itextframe/hyperlink_queries/) | 含まれるハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/ja/aspose.slides/itextframe/parent_shape/) | 親シェイプを返します。親オブジェクトが IShape インターフェイスを実装していない場合は None を返します。<br/>            読み取り専用 [`IShape`](/slides/python-net/ja/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ja/aspose.slides/itextframe/parent_cell/) | 親セルを返します。親オブジェクトが ICell インターフェイスを実装していない場合は None を返します。<br/>            読み取り専用 [`ICell`](/slides/python-net/ja/aspose.slides/icell). |
| [`slide`](/slides/python-net/ja/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/itextframe/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ja/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | 指定された色でサンプルテキストのすべての一致箇所をハイライトします。 |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ja/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | 指定された色でサンプルテキストのすべての一致箇所をハイライトします。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ja/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 指定された色でサンプルテキストのすべての一致箇所をハイライトします。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ja/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | 指定された色で正規表現のすべての一致箇所をハイライトします。 |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ja/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | 指定された色で正規表現のすべての一致箇所をハイライトします。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/itextframe/join_portions_with_same_formatting/#) | すべての段落で同じ書式設定のランを結合します。 |
| [`split_text_by_columns(self)`](/slides/python-net/ja/aspose.slides/itextframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe) のテキストコンテンツを文字列の配列に分割し、<br/>            各要素はフレーム内の別々のテキスト列に対応します。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ja/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 指定されたテキストのすべての出現を別の指定されたテキストに置き換えます。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ja/aspose.slides/itextframe/replace_regex/#str-str) | 正規表現のすべての一致箇所を指定された文字列に置き換えます。 |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)