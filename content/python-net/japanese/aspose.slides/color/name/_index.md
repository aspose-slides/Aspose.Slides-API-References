---
title: name property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/color/name/
weight: 190
---
## name プロパティ
この色の名前を取得します。<br/>            名前付きカラー（`Color.red` のような名前付き定数、または [`from_name`](/slides/python-net/ja/aspose.slides/color/from_name/) で作成されたカラー）の場合、.NET の名前が返されます。例：`"Red"` または `"LightBlue"`。<br/>            その他のカラーの場合、ARGB 値が先頭のゼロパディングなしの小文字の十六進数として返されます。例：`"ffff0000"`。`Color.empty.name` は `"0"`です。
            読み取り専用 **str**。

### 定義:
```python
@property
def name(self):
    ...
```


### 参照
* クラス [`Color`](/slides/python-net/ja/aspose.slides/color)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)