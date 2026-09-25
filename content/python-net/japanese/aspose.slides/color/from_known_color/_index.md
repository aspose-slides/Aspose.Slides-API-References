---
title: from_known_color method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
指定された事前定義カラーから色を作成します。<br/>これはシステムカラー（例: `KnownColor.CONTROL`）を取得する唯一の方法です。システムカラーはデスクトップテーマに依存するため `Color` 属性として公開されておらず、ライブラリのランタイムから読み取られます。

### 戻り値

このメソッドが作成する色です。

```python
@staticmethod
def from_known_color(known_color):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| known_color | **KnownColor** | `KnownColor` 列挙体の要素（.NET `System.Drawing.KnownColor` を鏡像した `IntEnum`）またはその整数値。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **ValueError** | その値は有効な `KnownColor` メンバーではありません。 |

### 参照
* クラス [`Color`](/slides/python-net/ja/aspose.slides/color)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)