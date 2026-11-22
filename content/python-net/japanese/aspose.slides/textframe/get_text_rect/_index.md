---
title: get_text_rect method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/textframe/get_text_rect/
weight: 10
---
## get_text_rect(self) {#}
親シェイプのジオメトリで定義されたテキスト矩形を取得します。

### 戻り値

テキスト領域を定義する[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)

```python
def get_text_rect(self):
    ...
```

### 備考

矩形の座標は親シェイプの左上隅を基準としています。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | テキストフレームがジオメトリシェイプに関連付けられていません。 |

### 参照
* クラス [`TextFrame`](/slides/python-net/ja/aspose.slides/textframe)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)