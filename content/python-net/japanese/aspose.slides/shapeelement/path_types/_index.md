---
title: path_types property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types プロパティ
要素のパス内の各ポイントのタイプを指定するバイト値の配列を取得します。

**0**  そのポイントが図形の開始点であることを示します。

**1**  そのポイントが線の 2 つの端点のうちの一つであることを示します。

**3**  そのポイントが 3 次ベジェスプラインの端点または制御点であることを示します。

**7**  下位 3 ビット（ポイントタイプを示す）以外のすべてのビットをマスクします。

**16**  対応するセグメントが破線であることを指定します。

**32**  そのポイントがマーカーであることを指定します。

**128**  そのポイントが閉じたサブパス（図形）の最後のポイントであることを指定します。

**129**  線分の端点であり、閉じたサブパスの最後のポイントでもあるデータポイントであることを示します。

### 定義:
```python
@property
def path_types(self):
    ...
```

### 参照
* クラス [`ShapeElement`](/slides/python-net/ja/aspose.slides/shapeelement)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)