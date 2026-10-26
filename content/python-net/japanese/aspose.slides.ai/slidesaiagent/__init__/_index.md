---
title: SlidesAIAgent constructor
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
組み込みの [`SlidesAIAgent`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent) の新しいインスタンスを初期化します
            [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient) をデフォルト構成で使用します。クライアントは
            Aspose の独自 LLM に接続し、追加の構成は不要です。別の AI クライアントを使用する場合は、**Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** のオーバーロードを使用してください。


```python
def __init__(self):
    ...
```



## __init__(self, ai_client) {#iaiwebclient}
カスタム AI クライアントで [`SlidesAIAgent`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent) の新しいインスタンスを初期化します
            このオーバーロードを使用して AI プロバイダーを指定したり、独自の LLM を提供したり、接続をカスタマイズしたりできます（例: 独自の `HttpClient` を提供する場合）。[`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient) の任意の実装を使用でき、以下を含みます：
            
* [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)


            デフォルト構成の組み込み [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient) を使用する場合は、**SlidesAIAgent.#ctor** のオーバーロードを使用してください。


```python
def __init__(self, ai_client):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient) | AI クライアント インスタンス。[`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient) の任意の実装を使用できます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | AI クライアント インスタンスが提供されていません。 |



### 参照
* クラス [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)
* クラス [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient)
* クラス [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)
* クラス [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)
* クラス [`SlidesAIAgent`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent)
* モジュール [`aspose.slides.ai`](/slides/python-net/ja/aspose.slides.ai)
* ライブラリ [`Aspose.Slides`](/slides/python-net)