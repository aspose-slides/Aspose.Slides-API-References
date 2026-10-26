---
title: TextFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/textframe/
---
## TextFrame クラス

TextFrame を表します。

The TextFrame type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`paragraphs`](/slides/python-net/ja/aspose.slides/textframe/paragraphs/) | フレーム内のすべての段落のリストを返します。<br/>            読み取り専用 [`IParagraphCollection`](/slides/python-net/ja/aspose.slides/iparagraphcollection)。 |
| [`text`](/slides/python-net/ja/aspose.slides/textframe/text/) | TextFrame のプレーンテキストを取得または設定します。<br/>            読み書き **str**。 |
| [`text_frame_format`](/slides/python-net/ja/aspose.slides/textframe/text_frame_format/) | この TextFrame オブジェクトの書式設定オブジェクトを返します。<br/>            読み取り専用 [`ITextFrameFormat`](/slides/python-net/ja/aspose.slides/itextframeformat)。 |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/textframe/hyperlink_queries/) | 含まれるハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/textframe/slide/) | TextFrame の親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/textframe/presentation/) | TextFrame の親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`parent_shape`](/slides/python-net/ja/aspose.slides/textframe/parent_shape/) | 親オブジェクトが IShape インターフェイスを実装していない場合、親シェイプまたは None を返します。<br/>            読み取り専用 [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。 |
| [`parent_cell`](/slides/python-net/ja/aspose.slides/textframe/parent_cell/) | 親オブジェクトが ICell インターフェイスを実装していない場合、親セルまたは None を返します。<br/>            読み取り専用 [`ICell`](/slides/python-net/ja/aspose.slides/icell)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ja/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | 指定された色でサンプルテキストのすべての一致箇所をハイライトします。 |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ja/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | 指定された色でサンプルテキストのすべての一致箇所をハイライトします。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ja/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 指定された色でサンプルテキストのすべての一致箇所をハイライトします。 |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ja/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | 指定された色で正規表現のすべての一致箇所をハイライトします。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ja/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | 指定された色で正規表現のすべての一致箇所をハイライトします。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/textframe/join_portions_with_same_formatting/#) | すべての段落で同じ書式設定のランを結合します。 |
| [`split_text_by_columns(self)`](/slides/python-net/ja/aspose.slides/textframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe) のテキストコンテンツを文字列の配列に分割し、<br/>            各要素はフレーム内の個別のテキスト列に対応します。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ja/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 指定されたテキストのすべての出現箇所を、別の指定されたテキストに置き換えます。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ja/aspose.slides/textframe/replace_regex/#str-str) | 正規表現のすべての一致箇所を指定された文字列に置き換えます。 |

### 関連項目
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)