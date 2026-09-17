---
title: SlidesAIAgent class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent クラス

プレゼンテーションの処理のための AI 搭載機能を提供します。

SlidesAIAgent 型は次のメンバーを公開します：

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | カスタム AI クライアントで [`SlidesAIAgent`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent) の新しいインスタンスを初期化します。<br/>            このオーバーロードを使用して AI プロバイダーを指定したり、独自の LLM を提供したり、接続をカスタマイズできます（例として、独自の `HttpClient` を提供する場合）。<br/>            [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient) の実装はすべて使用でき、以下を含みます：<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            組み込みの [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient) をデフォルト設定で使用するには、<br/>            代わりに **SlidesAIAgent.#ctor** オーバーロードを使用してください。 |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent/__init__/#) | [`SlidesAIAgent`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent) の新しいインスタンスを、組み込みの<br/>            [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient) をデフォルト設定で使用して初期化します。<br/>            クライアントは Aspose の独自 LLM に接続し、追加設定は必要ありません。<br/>            別の AI クライアントを使用する場合は、代わりに **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** オーバーロードを使用してください。 |

## メソッド

| Method | Description |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | テキスト記述からプレゼンテーションのインスタンスを生成します。必要な言語でトピック、アイデア、引用、またはテキストスニペットを提供してください。 |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | テキスト記述からプレゼンテーションのインスタンスを生成します。必要な言語でトピック、アイデア、引用、またはテキストスニペットを提供してください。 |
| [`translate(self, presentation, language)`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | AI を使用してプレゼンテーションを指定された言語に翻訳します（同期バージョン）。 |


### 参照
* クラス [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)
* クラス [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient)
* クラス [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)
* クラス [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)
* クラス [`SlidesAIAgent`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent)
* モジュール [`aspose.slides.ai`](/slides/python-net/ja/aspose.slides.ai)
* ライブラリ [`Aspose.Slides`](/slides/python-net)