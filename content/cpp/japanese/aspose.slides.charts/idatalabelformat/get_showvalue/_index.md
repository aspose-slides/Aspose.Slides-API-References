---
title: get_ShowValue()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。True はパーセンテージ値を表示し、False は非表示にします。読み取り bool。
type: docs
weight: 118
url: /ja/aspose.slides.charts/idatalabelformat/get_showvalue/
---
## IDataLabelFormat::get_ShowValue() メソッド

指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。True はパーセンテージ値を表示し、False は非表示にします。読み取り **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowValue()=0
```

## 備考

この [DataLabelFormat](../../datalabelformat/) オブジェクトの親が [DataLabelCollection](../../datalabelcollection/) データ ラベルのコレクションである場合、このプロパティは [DataLabelCollection](../../datalabelcollection/) コレクション内の新しいデータ ラベルの ShowValue プロパティの既定値を取得または設定します。値を設定すると、この値は [DataLabelCollection](../../datalabelcollection/) コレクション内のすべてのデータ ラベルの ShowValue プロパティにも設定されます（例: "DataLabels.DefaultDataLabelFormat.ShowValue = val;" になると、すべての DataLabels[i].ShowValue が val と等しくなります）。

## 参照

* クラス [IDataLabelFormat](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)