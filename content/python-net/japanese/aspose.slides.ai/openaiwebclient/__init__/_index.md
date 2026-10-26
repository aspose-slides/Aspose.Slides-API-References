---
title: OpenAIWebClient constructor
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
OpenAI ウェブクライアントのインスタンスを作成します。


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| model | **str** | OpenAI 言語モデル。利用可能な値：<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI APIキー。 |
| organization_id | **str** | Organization ID（オプション）。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | APIキーの値は None または空にできません。 |
| **RuntimeError(Proxy error(ArgumentException))** | テキストモデルの値は None または空にできません。 |



### 参照
* クラス [`OpenAIWebClient`](/slides/python-net/ja/aspose.slides.ai/openaiwebclient)
* モジュール [`aspose.slides.ai`](/slides/python-net/ja/aspose.slides.ai)
* ライブラリ [`Aspose.Slides`](/slides/python-net)