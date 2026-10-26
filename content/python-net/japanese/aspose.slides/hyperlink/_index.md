---
title: Hyperlink class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/hyperlink/
---
## Hyperlink クラス

ハイパーリンクを表します。

**継承:**[`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)

Hyperlink 型は次のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/ja/aspose.slides/hyperlink/__init__/#str) | ハイパーリンクのインスタンスを作成します。 |
| [`__init__(self, slide)`](/slides/python-net/ja/aspose.slides/hyperlink/__init__/#islide) | 特定のスライドを指すハイパーリンクのインスタンスを作成します。<br/>            注: 作成されたハイパーリンクは同じプレゼンテーション内のオブジェクトに割り当てる必要があります。割り当てない場合、リンクは NoAction として保存されます。 |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/ja/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | 別のハイパーリンクをソースとして使用し、二次プロパティを上書きしたハイパーリンクのインスタンスを作成します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`no_action`](/slides/python-net/ja/aspose.slides/hyperlink/no_action/) | 特別な「何もしない」ハイパーリンクを返します。<br/>            読み取り専用 [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)。 |
| [`media`](/slides/python-net/ja/aspose.slides/hyperlink/media/) | 特別な「メディアファイルを再生」ハイパーリンクを返します。AudioFrame と VideoFrame で使用されます。<br/>            読み取り専用 [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)。 |
| [`next_slide`](/slides/python-net/ja/aspose.slides/hyperlink/next_slide/) | 次のスライドへのハイパーリンクを返します。<br/>            読み取り専用 [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)。 |
| [`previous_slide`](/slides/python-net/ja/aspose.slides/hyperlink/previous_slide/) | 前のスライドへのハイパーリンクを返します。<br/>            読み取り専用 [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)。 |
| [`first_slide`](/slides/python-net/ja/aspose.slides/hyperlink/first_slide/) | プレゼンテーションの最初のスライドへのハイパーリンクを返します。<br/>            読み取り専用 [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)。 |
| [`last_slide`](/slides/python-net/ja/aspose.slides/hyperlink/last_slide/) | プレゼンテーションの最後のスライドへのハイパーリンクを返します。<br/>            読み取り専用 [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)。 |
| [`last_vieved_slide`](/slides/python-net/ja/aspose.slides/hyperlink/last_vieved_slide/) | 最後に表示したスライドへのハイパーリンクを返します。<br/>            読み取り専用 [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)。 |
| [`end_show`](/slides/python-net/ja/aspose.slides/hyperlink/end_show/) | ショーを終了するハイパーリンクを返します。<br/>            読み取り専用 [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)。 |
| [`action_type`](/slides/python-net/ja/aspose.slides/hyperlink/action_type/) | Hyperlink のアクションの種類を返します。<br/>            読み取り専用 [`HyperlinkActionType`](/slides/python-net/ja/aspose.slides/hyperlinkactiontype)。 |
| [`external_url`](/slides/python-net/ja/aspose.slides/hyperlink/external_url/) | 外部 URL を指定します。<br/>            読み取り専用 **str**。 |
| [`target_slide`](/slides/python-net/ja/aspose.slides/hyperlink/target_slide/) | Hyperlink が特定スライドを対象としている場合、そのスライドを返します。<br/>            読み取り専用 [`ISlide`](/slides/python-net/ja/aspose.slides/islide)。 |
| [`external_url_original`](/slides/python-net/ja/aspose.slides/hyperlink/external_url_original/) | 実際のコンテンツに関係なくこの部分に設定されたハイパーリンクを表します。<br/>            <br/>            PowerPoint はリンクとそのテキストに対して特別な動作を行います。実際のリンク先とは異なる有効な URL 形式のテキストをハイパーリンクとして作成できます。この場合、編集ウィンドウでリンクを表示するとテキスト部分に合わせて変更されます。このプロパティはハイパーリンクの元の値を表します。 |
| [`target_frame`](/slides/python-net/ja/aspose.slides/hyperlink/target_frame/) | 親ハイパーリンクの対象が存在する場合、親 HTML フレームセット内のフレームを返します。<br/>            読み書き **str**。 |
| [`tooltip`](/slides/python-net/ja/aspose.slides/hyperlink/tooltip/) | ユーザーインターフェイスに表示される可能性のある文字列を返します。<br/>            読み書き **str**。 |
| [`history`](/slides/python-net/ja/aspose.slides/hyperlink/history/) | 親ハイパーリンクが呼び出されたときに、対象を表示済みハイパーリンクのリストに追加するかどうかを決定します。<br/>            読み書き **bool**。 |
| [`highlight_click`](/slides/python-net/ja/aspose.slides/hyperlink/highlight_click/) | クリック時にハイパーリンクをハイライト表示するかどうかを決定します。<br/>            読み書き **bool**。 |
| [`stop_sound_on_click`](/slides/python-net/ja/aspose.slides/hyperlink/stop_sound_on_click/) | クリック時にサウンドを停止するかどうかを決定します。<br/>            読み書き **bool**。 |
| [`sound`](/slides/python-net/ja/aspose.slides/hyperlink/sound/) | ハイパーリンクの再生サウンドを表します。<br/>            読み書き [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)。 |
| [`color_source`](/slides/python-net/ja/aspose.slides/hyperlink/color_source/) | ハイパーリンクの色のソース（スタイルまたは部分書式）を表します。<br/>            読み書き [`HyperlinkColorSource`](/slides/python-net/ja/aspose.slides/hyperlinkcolorsource)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/hyperlink/presentation/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/ja/aspose.slides/hyperlink/equals/#ihyperlink) | 2 つの Hyperlink インスタンスが等しいかどうかを判断します。 |

### 参照
* クラス [`Hyperlink`](/slides/python-net/ja/aspose.slides/hyperlink)
* クラス [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)