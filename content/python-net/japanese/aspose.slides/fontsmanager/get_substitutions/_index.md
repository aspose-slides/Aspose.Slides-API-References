---
title: get_substitutions method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/fontsmanager/get_substitutions/
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
指定されたスライドのレンダリング中に置換されるフォントに関する情報を取得します。

### 戻り値

指定されたスライドのすべてのフォント置換のコレクション ([`FontSubstitutionInfo`](/slides/python-net/ja/aspose.slides/fontsubstitutioninfo))です。



```python
def get_substitutions(self, slides):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slides | **List[int]** | フォント置換情報を取得する対象スライドのインデックス配列（1から開始）。 |



### 参照
* クラス [`FontsManager`](/slides/python-net/ja/aspose.slides/fontsmanager)
* クラス [`FontSubstitutionInfo`](/slides/python-net/ja/aspose.slides/fontsubstitutioninfo)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)