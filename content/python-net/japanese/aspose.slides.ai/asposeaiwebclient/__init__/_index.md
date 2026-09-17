---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides 用 Python 経由 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
デフォルトの Aspose LLM エンドポイントに接続する Aspose AI web client のインスタンスを作成します。これはパラメータなしの **SlidesAIAgent.#ctor** コンストラクタで使用されるクライアントです。そのため、クライアントを **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** コンストラクタに直接渡す場合にのみ、明示的に作成する必要があります。

```python
def __init__(self):
    ...
```

## __init__(self, url) {#str}
カスタムエンドポイント URL に接続する Aspose AI web client のインスタンスを作成します。Aspose.Slides チームが提供する URL がある場合はこのオーバーロードを使用し、そうでない場合はデフォルト URL の **AsposeAIWebClient.#ctor** オーバーロードを使用してください。

```python
def __init__(self, url):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| url | **str** | Aspose LLM のエンドポイント URL（Aspose.Slides チーム提供）。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL は None または空にできません。 |

### 参照
* クラス [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)
* モジュール [`aspose.slides.ai`](/slides/python-net/ja/aspose.slides.ai)
* ライブラリ [`Aspose.Slides`](/slides/python-net)