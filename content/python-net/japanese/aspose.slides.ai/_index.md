---
title: aspose.slides.ai
second_title: Aspose.Slides for Python の .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ai/
---
PowerPoint プレゼンテーションの分析と処理のための AI ベース機能を提供するクラスを含みます。

## クラス

| クラス | 説明 |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/ja/aspose.slides.ai/asposeaiwebclient/) | ビルトイン [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient) 実装で、Aspose の独自 LLM に接続します。<br/>            パラメータなし **SlidesAIAgent.#ctor** コンストラクタで使用されるデフォルト クライアントです。 |
| [`IAIConversation`](/slides/python-net/ja/aspose.slides.ai/iaiconversation/) | 会話インスタンスを表します。通常の AI 呼び出しとは異なり、会話は全体のコンテキストを保持します。 |
| [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient/) | AI Web クライアント インターフェイスです。このインターフェイスにより、さまざまな AI 言語モデルに差し替えることができます。<br/>            このインターフェイスを実装するクラスは `SlidesAIAgent` と共に使用されることが想定されています。 |
| [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient/) | ビルトイン [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient) 実装で、指定されたベース URL の OpenAI 互換 LLM プロバイダーに接続します。 |
| [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient/) | ビルトイン [`IAIWebClient`](/slides/python-net/ja/aspose.slides.ai/iaiwebclient) 実装で、OpenAI API に接続します。 |
| [`SlidesAIAgent`](/slides/python-net/ja/aspose.slides.ai/slidesaiagent/) | プレゼンテーションの処理のための AI 機能を提供します。 |
| [`SlidesAIAgentException`](/slides/python-net/ja/aspose.slides.ai/slidesaiagentexception/) | Slides AI エージェント関連の例外を表します。 |

## 列挙体

| 列挙体 | 説明 |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/ja/aspose.slides.ai/presentationcontentamounttype/) | 生成されたプレゼンテーションに含まれるコンテンツ量を指定します。これにより、スライド数とスライドごとの詳細度の両方が影響を受けます。 |