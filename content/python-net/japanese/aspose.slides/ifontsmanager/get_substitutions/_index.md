---
title: get_substitutions method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ifontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
プレゼンテーションのレンダリング時に置換されるフォントに関する情報を取得します。

### 戻り値

すべてのフォント置換のコレクション [`FontSubstitutionInfo`](/slides/python-net/ja/aspose.slides/fontsubstitutioninfo)。

```python
def get_substitutions(self):
    ...
```

## get_substitutions(self, slides) {#listint}
指定されたスライドのレンダリング時に置換されるフォントに関する情報を取得します。

### 戻り値

指定されたスライド用のすべてのフォント置換のコレクション ([`FontSubstitutionInfo`](/slides/python-net/ja/aspose.slides/fontsubstitutioninfo))。

```python
def get_substitutions(self, slides):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slides | **List[int]** | フォント置換情報を取得するスライドインデックスの配列、1 から開始。 |

### 参照
* クラス [`FontSubstitutionInfo`](/slides/python-net/ja/aspose.slides/fontsubstitutioninfo)
* クラス [`IFontsManager`](/slides/python-net/ja/aspose.slides/ifontsmanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)