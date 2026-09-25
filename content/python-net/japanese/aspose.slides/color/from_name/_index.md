---
title: from_name method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
指定された事前定義カラー名から色を作成します。<br/>検索は大文字小文字を区別せず、アンダースコアとスペースを無視します: `"LightBlue"`、`"lightblue"`、`"light_blue"` はすべて `Color.light_blue` に解決されます。[`Color`](/slides/python-net/ja/aspose.slides/color) クラス ページで事前定義カラーの一覧をご覧ください。

### 戻り値

名前付きカラー。

```python
@staticmethod
def from_name(name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| name | **str** | 事前定義されたカラーの名前を示す文字列。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **ValueError** | 名前が事前定義カラーの名前ではありません。 |
| **TypeError** | 名前が文字列ではありません。 |

### 参照
* クラス [`Color`](/slides/python-net/ja/aspose.slides/color)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)