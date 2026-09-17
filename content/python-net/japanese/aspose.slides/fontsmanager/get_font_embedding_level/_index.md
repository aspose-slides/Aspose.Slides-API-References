---
title: get_font_embedding_level method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
指定されたバイト配列およびフォント名からフォントの埋め込みレベルを決定します。

### Returns
指定されたフォントの埋め込みレベル。

```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| font_bytes | **bytes** | フォントデータを含むバイト配列。 |
| font_name | **str** | フォントの名前。 |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `font_bytes` が None のときにスローされます。 |

### See Also
* 列挙体 [`EmbeddingLevel`](/slides/python-net/ja/aspose.slides/embeddinglevel)
* クラス [`FontsManager`](/slides/python-net/ja/aspose.slides/fontsmanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)