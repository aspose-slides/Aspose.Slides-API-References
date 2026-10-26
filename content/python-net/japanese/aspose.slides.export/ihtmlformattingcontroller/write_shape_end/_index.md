---
title: write_shape_end method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
shape のレンダリングの前に呼び出されます。各 shape ごとに 1 回呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、追加された HTML フラグメントが挿入され、以前の画像の上に新しい画像が開始されます。

```python
def write_shape_end(self, generator, shape):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator) | 出力オブジェクト。 |
| shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | 最後にレンダリングされる Shape。 |

### 参照
* クラス [`IHtmlFormattingController`](/slides/python-net/ja/aspose.slides.export/ihtmlformattingcontroller)
* クラス [`IHtmlGenerator`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator)
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)