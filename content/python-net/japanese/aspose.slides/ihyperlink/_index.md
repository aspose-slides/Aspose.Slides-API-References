---
title: IHyperlink class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ihyperlink/
---
## IHyperlink クラス

ハイパーリンクを表します。

IHyperlink 型は以下のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`action_type`](/slides/python-net/ja/aspose.slides/ihyperlink/action_type/) | HyperLinkEx のアクションの型を返します。<br/>            読み取り専用 [`HyperlinkActionType`](/slides/python-net/ja/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/ja/aspose.slides/ihyperlink/external_url/) | 外部 URL を指定します。<br/>            このプロパティが None でなくなると、TargetSlide プロパティは None になります。<br/>            読み取り専用 **str**. |
| [`external_url_original`](/slides/python-net/ja/aspose.slides/ihyperlink/external_url_original/) | この部分の実際の内容に関係なく設定されたハイパーリンクを表します。<br/>            <br/>            PowerPoint はリンクとそれに対応するテキストに対して特別な動作をします。リンクの実際のアドレスとは異なる有効な URL 形式でハイパーリンク用のテキストを作成できます。この場合、編集ウィンドウでリンクを表示すると、テキスト部分に合わせて変更されます。このプロパティはハイパーリンクの元の値を表します。 |
| [`target_slide`](/slides/python-net/ja/aspose.slides/ihyperlink/target_slide/) | HyperlinkEx が特定のスライドを対象とする場合、そのスライドを返します。<br/>            このプロパティが None でなくなると、ExternalUrl プロパティは None になります。<br/>            読み取り専用 [`ISlide`](/slides/python-net/ja/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/ja/aspose.slides/ihyperlink/target_frame/) | 親ハイパーリンクのターゲットが存在する場合、親 HTML フレームセット内のフレームを返します。<br/>            読み書き **str**. |
| [`tooltip`](/slides/python-net/ja/aspose.slides/ihyperlink/tooltip/) | 親ハイパーリンクに関連付けられたユーザーインターフェイスに表示される可能性のある文字列を返します。<br/>            読み書き **str**. |
| [`history`](/slides/python-net/ja/aspose.slides/ihyperlink/history/) | 親ハイパーリンクのターゲットが呼び出されたときに、閲覧されたハイパーリンクのリストに追加されるかどうかを決定します。<br/>            読み書き **bool**. |
| [`highlight_click`](/slides/python-net/ja/aspose.slides/ihyperlink/highlight_click/) | クリック時にハイパーリンクをハイライト表示すべきかどうかを決定します。<br/>            読み書き **bool**. |
| [`stop_sound_on_click`](/slides/python-net/ja/aspose.slides/ihyperlink/stop_sound_on_click/) | ハイパーリンククリック時にサウンドを停止すべきかどうかを決定します。<br/>            読み書き **bool**. |
| [`sound`](/slides/python-net/ja/aspose.slides/ihyperlink/sound/) | ハイパーリンクの再生中サウンドを表します。<br/>            読み書き [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/ja/aspose.slides/ihyperlink/color_source/) | ハイパーリンクの色のソース（スタイルまたは部分書式）を表します。<br/>            読み書き [`HyperlinkColorSource`](/slides/python-net/ja/aspose.slides/hyperlinkcolorsource). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/ja/aspose.slides/ihyperlink/equals/#ihyperlink) | 2 つの Hyperlink インスタンスが等しいかどうかを判定します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)