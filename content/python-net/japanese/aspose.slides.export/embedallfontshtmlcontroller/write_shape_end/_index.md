---
title: write_shape_end method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}

shape の描画前に呼び出されます。各 shape ごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

```python
def write_shape_end(self, generator, shape):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator) | 出力オブジェクト。 |
| shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | 最後に描画されるシェイプ。 |

### 参照
* クラス [`EmbedAllFontsHtmlController`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller)
* クラス [`IHtmlGenerator`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator)
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)