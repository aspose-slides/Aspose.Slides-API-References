---
title: translate method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
AI を使用してプレゼンテーションを指定された言語に変換します（同期バージョン）。

```python
def translate(self, presentation, language):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) | 対象のプレゼンテーション |
| language | **str** | 対象言語 |

### 備考

以下の例はデフォルトの[`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)を使用します。これはパラメータなしの**SlidesAIAgent.#ctor**コンストラクタで作成され、Aspose の独自 LLM に接続します。別の AI プロバイダーを使用するには、独自の LLM を提供するか、接続をカスタマイズします（例として、独自の `HttpClient` を提供する）。**Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** コンストラクタに [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient) 実装を渡します。利用可能な実装は以下です：

* [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | プレゼンテーション インスタンスが提供されていません |
| **RuntimeError(Proxy error(ArgumentException))** | 言語の値が None または空にできません |

### 参照
* クラス [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)
* クラス [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient)
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* クラス [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)
* クラス [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)
* クラス [`SlidesAIAgent`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent)
* モジュール [`aspose.slides.ai`](/slides/python-net/ja/aspose.slides.ai)
* ライブラリ [`Aspose.Slides`](/slides/python-net)