---
title: separator property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## 区切り文字 プロパティ
チャートのデータラベルで使用される区切り文字を表す Variant を設定または取得します。
読み取り/書き込み **str**。


### 備考

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection コレクション内の新しいデータラベルの Separator プロパティのデフォルト値を取得または設定します。  
このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータラベルの Separator プロパティにも同じ値が設定されます。  
（例: `DataLabels.DefaultDataLabelFormat.Separator = val;` はすべての DataLabels[i].Separator が val と等しくなることを意味します。）

### 定義:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### 参照
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)