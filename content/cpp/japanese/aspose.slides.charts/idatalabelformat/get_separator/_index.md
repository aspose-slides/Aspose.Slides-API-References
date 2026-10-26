---
title: get_Separator()
second_title: Aspose.Slides for C++ API リファレンス
description: "チャート上のデータラベルで使用される区切り文字を表す Variant を設定または取得します。System::String を参照してください。"
type: docs
weight: 326
url: /ja/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() method

チャート上のデータラベルで使用される区切り文字を表す Variant を設定または取得します。[System::String](../../../system/string/) を参照してください。

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## 備考

この [DataLabelFormat](../../datalabelformat/) オブジェクトの親がデータラベルの [DataLabelCollection](../../datalabelcollection/) コレクションである場合、このプロパティは [DataLabelCollection](../../datalabelcollection/) コレクション内の新しいデータラベルの Separator プロパティの既定値を取得または設定します。値を設定すると、この値は [DataLabelCollection](../../datalabelcollection/) コレクション内のすべてのデータラベルの Separator プロパティにも設定されます（例: `DataLabels.DefaultDataLabelFormat.Separator = val;` によりすべての DataLabels[i].Separator が val と同じになります）。

## 参照

* クラス [String](../../../system/string/)
* クラス [IDataLabelFormat](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)