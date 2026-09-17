---
title: AsposeAIWebClient class
second_title: Python 用 Aspose.Slides (.NET API リファレンス)
description: 
type: docs
url: /ja/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient クラス

Aspose独自のLLMに接続する組み込み[`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient)実装です。            パラメータなしの**SlidesAIAgent.#ctor**コンストラクタで使用されるデフォルトクライアントです。

AsposeAIWebClient型は次のメンバーを公開します:

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient/__init__/#) | デフォルトのAspose LLMエンドポイントに接続するAspose AIウェブクライアントのインスタンスを作成します。<br/>            これはパラメータなしの**SlidesAIAgent.#ctor**コンストラクタで使用されるクライアントであり、クライアントを**Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**コンストラクタに直接渡す場合にのみ、明示的に作成する必要があります。 |
| [`__init__(self, url)`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient/__init__/#str) | カスタムエンドポイントURLに接続するAspose AIウェブクライアントのインスタンスを作成します。この<br/>            オーバーロードは、Aspose.Slidesチームが提供するURLがある場合に使用します。そうでない場合は、デフォルトURLを使用した**AsposeAIWebClient.#ctor**オーバーロードを使用してください。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | 会話インスタンスを作成します。通常のAI呼び出しとは異なり、会話は全体のコンテキストを保持します。 |


### 参照
* クラス [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient)
* モジュール [`aspose.slides.ai`](/slides/python-net/ja/aspose.slides.ai)
* ライブラリ [`Aspose.Slides`](/slides/python-net)