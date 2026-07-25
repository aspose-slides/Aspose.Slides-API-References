---
title: set_ShowSeriesName()
second_title: Aspose.Slides for C++ APIリファレンス
description: チャート上のデータラベルのシリーズ名表示動作を示すブール値を設定します。True でシリーズ名を表示し、False で非表示にします。bool を書き込みます。
type: docs
weight: 183
url: /ja/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) メソッド


チャート上のデータ ラベルのシリーズ名表示動作を示すために、ブール値を設定します。True でシリーズ名を表示し、False で非表示にします。**bool** を書き込みます。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## 備考


この [DataLabelFormat](../../datalabelformat/) オブジェクトの親がデータ ラベルの [DataLabelCollection](../../datalabelcollection/) コレクションである場合、このプロパティは [DataLabelCollection](../../datalabelcollection/) コレクション内の新しいデータ ラベルに対する ShowSeriesName プロパティの既定値を取得または設定します。値を設定すると、この値は [DataLabelCollection](../../datalabelcollection/) コレクション内のすべてのデータ ラベルの ShowSeriesName プロパティにも設定されます（例: "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" により、すべての DataLabels[i].ShowSeriesName が val と等しくなります）。


## 参照

* クラス [IDataLabelFormat](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)