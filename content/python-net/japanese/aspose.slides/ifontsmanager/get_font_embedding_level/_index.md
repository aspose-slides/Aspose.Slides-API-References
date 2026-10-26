---
title: get_font_embedding_level method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
指定されたバイト配列とフォント名からフォントの埋め込みレベルを判定します。

### 戻り値

指定されたフォントの埋め込みレベルです。

```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| font_bytes | **bytes** | フォントデータを含むバイト配列です。 |
| font_name | **str** | フォントの名前です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `font_bytes` が None の場合にスローされます。 |

### 参照
* 列挙型 [`EmbeddingLevel`](/slides/python-net/ja/aspose.slides/embeddinglevel)
* クラス [`IFontsManager`](/slides/python-net/ja/aspose.slides/ifontsmanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)