---
title: write_shape_start method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
シェイプのレンダリング前に呼び出されます。各シェイプにつき1回呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が完了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

```python
def write_shape_start(self, generator, shape):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator) | 出力オブジェクト。 |
| shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | レンダリングされようとしているシェイプ。 |

### 参照
* クラス [`EmbedAllFontsHtmlController`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller)
* クラス [`IHtmlGenerator`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator)
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)