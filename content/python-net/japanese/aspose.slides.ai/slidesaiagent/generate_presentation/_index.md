---
title: generate_presentation method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
テキスト説明からプレゼンテーションインスタンスを生成します。必要な言語でトピック、アイデア、引用文、またはテキストスニペットを提供してください。

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| description | **str** | トピック、アイデア、引用文、またはテキストスニペット。 |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/ja/aspose.slides.ai/presentationcontentamounttype) | 生成されるプレゼンテーションのコンテンツ量。 |

### 備考

以下の例はデフォルトの[`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)を使用しています。これはパラメータなしの **SlidesAIAgent.#ctor** コンストラクタによって作成され、Aspose の独自 LLM に接続します。別の AI プロバイダーを使用する場合、独自の LLM を提供するか、接続をカスタマイズ（例: 独自の `HttpClient` を提供）して、**Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** コンストラクタに[`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient)実装を渡してください。利用可能な実装は次のとおりです：

* [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | AI チャット指示は None または空にできません。 |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
テキスト説明からプレゼンテーションインスタンスを生成します。必要な言語でトピック、アイデア、引用文、またはテキストスニペットを提供してください。

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| description | **str** | トピック、アイデア、引用文、またはテキストスニペット。 |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/ja/aspose.slides.ai/presentationcontentamounttype) | 生成されるプレゼンテーションのコンテンツ量。 |
| presentation_template | [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) | デフォルトテンプレートの代わりにレイアウトとデザインのテンプレートとして使用するプレゼンテーション。 |

### 備考

以下の例はデフォルトの[`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)を使用しています。これはパラメータなしの **SlidesAIAgent.#ctor** コンストラクタによって作成され、Aspose の独自 LLM に接続します。別の AI プロバイダーを使用する場合、独自の LLM を提供するか、接続をカスタマイズ（例: 独自の `HttpClient` を提供）して、**Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** コンストラクタに[`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient)実装を渡してください。利用可能な実装は次のとおりです：

* [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | プレゼンテーションテンプレートが提供されていません。 |
| **RuntimeError(Proxy error(ArgumentException))** | AI チャット指示は None または空にできません。 |

### 参照
* クラス [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient)
* クラス [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient)
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* クラス [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)
* クラス [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)
* 列挙体 [`PresentationContentAmountType`](/slides/python-net/ja/aspose.slides.ai/presentationcontentamounttype)
* クラス [`SlidesAIAgent`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent)
* モジュール [`aspose.slides.ai`](/slides/python-net/ja/aspose.slides.ai)
* ライブラリ [`Aspose.Slides`](/slides/python-net)