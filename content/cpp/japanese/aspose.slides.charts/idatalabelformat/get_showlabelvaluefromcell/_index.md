---
title: get_ShowLabelValueFromCell()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたチャートのデータ ラベル セル値の表示動作を表します。True はセル値を表示し、False は非表示にします。読み取り型は boolです。
type: docs
weight: 300
url: /ja/aspose.slides.charts/idatalabelformat/get_showlabelvaluefromcell/
---
## IDataLabelFormat::get_ShowLabelValueFromCell() メソッド


指定されたチャートのデータ ラベル セル値の表示動作を表します。True はセル値を表示します。False は非表示にします。読み取り **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelValueFromCell()=0
```

## 備考


この [DataLabelFormat](../../datalabelformat/) オブジェクトの親が [DataLabelCollection](../../datalabelcollection/) データ ラベルのコレクションである場合、このプロパティは [DataLabelCollection](../../datalabelcollection/) コレクション内の新しいデータ ラベルの ShowLabelValueFromCell プロパティの既定値を取得または設定します。値を指定してこのプロパティを設定すると、[DataLabelCollection](../../datalabelcollection/) コレクション内のすべてのデータ ラベルの ShowLabelValueFromCell プロパティにも同じ値が設定されます（例: \"DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;\" はすべての DataLabels[i].ShowLabelValueFromCell が val と等しくなる原因となります）。

## 参照

* クラス [IDataLabelFormat](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)