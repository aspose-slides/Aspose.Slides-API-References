---
title: get_NumberFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: "DataLabels オブジェクトの書式文字列を表します。System::String を参照してください。"
type: docs
weight: 27
url: /ja/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() メソッド


DataLabels オブジェクトの書式文字列を表します。[System::String](../../../system/string/) を参照してください。

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## 備考



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



この [DataLabelFormat](../) オブジェクトの親がデータ ラベルの [DataLabelCollection](../../datalabelcollection/) コレクションである場合、このプロパティは [DataLabelCollection](../../datalabelcollection/) コレクション内の新しいデータ ラベルの NumberFormat プロパティのデフォルト値を取得または設定します。  
このプロパティに値を設定すると、その値は [DataLabelCollection](../../datalabelcollection/) コレクション内のすべてのデータ ラベルの NumberFormat プロパティにも設定されます（例: "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" はすべての DataLabels[i].NumberFormat を val に等しくします）。


## 参照

* クラス [String](../../../system/string/)
* クラス [DataLabelFormat](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)