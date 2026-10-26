---
title: NotesSlide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/notesslide/
---
## NotesSlide クラス

プレゼンテーション内のノートスライドを表します。

**Inheritance:**[`NotesSlide`](/slides/python-net/ja/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)

NotesSlide 型は以下のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`shapes`](/slides/python-net/ja/aspose.slides/notesslide/shapes/) | スライドのシェイプを返します。<br/>            読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/ja/aspose.slides/notesslide/controls/) | スライド上の ActiveX コントロールのコレクションを返します。<br/>            読み取り専用 [`IControlCollection`](/slides/python-net/ja/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/ja/aspose.slides/notesslide/name/) | スライドの名前を取得または設定します。<br/>            読み書き **str**。 |
| [`slide_id`](/slides/python-net/ja/aspose.slides/notesslide/slide_id/) | スライドの ID を返します。<br/>            読み取り専用 **int**。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/notesslide/custom_data/) | スライドのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/ja/aspose.slides/notesslide/timeline/) | アニメーションタイムラインオブジェクトを返します。<br/>            読み取り専用 [`IAnimationTimeLine`](/slides/python-net/ja/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/notesslide/slide_show_transition/) | 指定されたスライドがスライドショー中にどのように進むかに関する情報を含む Transition オブジェクトを返します。<br/>            読み取り専用 [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/ja/aspose.slides/notesslide/background/) | スライドの背景を返します。<br/>            読み取り専用 [`IBackground`](/slides/python-net/ja/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/notesslide/hyperlink_queries/) | 含まれるハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/notesslide/show_master_shapes/) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。<br/>            読み書き **bool**。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/notesslide/presentation/) | IPresentation インターフェイスを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/notesslide/header_footer_manager/) | ノートスライドの HeaderFooter マネージャーを返します。<br/>            読み取り専用 [`INotesSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/inotesslideheaderfootermanager)。 |
| [`notes_text_frame`](/slides/python-net/ja/aspose.slides/notesslide/notes_text_frame/) | ノートのテキストがある場合、TextFrame を返します。<br/>            読み取り専用 [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe)。 |
| [`theme_manager`](/slides/python-net/ja/aspose.slides/notesslide/theme_manager/) | 上書きテーママネージャーを返します。<br/>            読み取り専用 [`IOverrideThemeManager`](/slides/python-net/ja/aspose.slides.theme/ioverridethememanager)。 |
| [`parent_slide`](/slides/python-net/ja/aspose.slides/notesslide/parent_slide/) | 親スライドを返します。<br/>            読み取り専用 [`ISlide`](/slides/python-net/ja/aspose.slides/islide)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/notesslide/slide/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/notesslide/join_portions_with_same_formatting/#) | すべての許容可能なシェイプ内のすべての段落において、同じ書式のランを結合します。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ja/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | すべての許容可能なシェイプ内のすべての段落において、同じ書式のランを結合します。 |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/notesslide/equals/#ibaseslide) | 2 つの IBaseSlide インスタンスが等しいかどうかを判断します。<br/>            返される値はスライドの構造と静的コンテンツに基づいて計算されます。<br/>            すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、スライドは等しいとみなされます。比較は SlideId などの固有識別子や、日付プレースホルダーの現在の日付値などの動的コンテンツは考慮しません。 |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/notesslide/create_theme_effective/#) | このスライドの有効なテーマを返します。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/notesslide/find_shape_by_alt_text/#str) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |

### 参照
* クラス [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)
* クラス [`NotesSlide`](/slides/python-net/ja/aspose.slides/notesslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)