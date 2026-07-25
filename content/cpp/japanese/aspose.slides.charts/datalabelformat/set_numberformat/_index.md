---
title: set_NumberFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: "DataLabels オブジェクトの書式文字列を表します。System::String を書き込みます。"
type: docs
weight: 40
url: /ja/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) メソッド

DataLabels オブジェクトの書式文字列を表します。[System::String](../../../system/string/) を書き込みます。

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## 備考


```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```


この [DataLabelFormat](../) オブジェクトの親がデータラベルの [DataLabelCollection](../../datalabelcollection/) コレクションである場合、このプロパティは [DataLabelCollection](../../datalabelcollection/) コレクション内の新しいデータラベルに対する NumberFormat プロパティのデフォルト値を取得または設定します。このプロパティに値を設定すると、その値は [DataLabelCollection](../../datalabelcollection/) コレクション内のすべてのデータラベルの NumberFormat プロパティにも設定されます（例: "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" はすべての DataLabels[i].NumberFormat が val に等しくなることを引き起こします）。



## 参照

* クラス [String](../../../system/string/)
* クラス [DataLabelFormat](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)