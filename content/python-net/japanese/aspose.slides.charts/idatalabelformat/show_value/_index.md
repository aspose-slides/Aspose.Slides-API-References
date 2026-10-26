---
title: show_value property
second_title: Python 用 Aspose.Slides via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value プロパティ
指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。 
True はパーセンテージ値を表示します。False は非表示にします。
読み取り/書き込み **bool**。


### 備考

この DataLabelFormat オブジェクトの親がデータ ラベルの DataLabelCollection コレクションである場合、この プロパティは DataLabelCollection コレクション内の新しいデータ ラベルに対する ShowValue Property の既定値を取得または設定します。  
この プロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータ ラベルの ShowValue プロパティにも同じ値が設定されます（例: "DataLabels.DefaultDataLabelFormat.ShowValue = val;" はすべての DataLabels[i].ShowValue が val と等しくなることを意味します）。


### 定義：
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### 参照
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)