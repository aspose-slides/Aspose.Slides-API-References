---
title: get_IsVisible()
second_title: Aspose.Slides for C++ API リファレンス
description: False は、データ ラベルがデフォルトで表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-flags (ShowValue, ...) が false になります)。 読み取り専用 bool。
type: docs
weight: 14
url: /ja/aspose.slides.charts/datalabelcollection/get_isvisible/
---
## DataLabelCollection::get_IsVisible() メソッド

False は、データ ラベルがデフォルトで表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-flags (ShowValue, ...) が false になります)。 読み取り専用 **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelCollection::get_IsVisible() override
```

## 備考

データ ラベルがデフォルトで表示されている場合は、[Hide()](../hide/) メソッドを使用してデフォルトで非表示にできます。 ただし、データ ラベルがデフォルトで表示されない場合 (IsVisible は false) は、DefaultDataLabelFormat プロパティの Show*-flags (ShowValue, ...) を true に設定することでデータ ラベルを「デフォルトで表示」にすることができます。

## 参照

* クラス [DataLabelCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)