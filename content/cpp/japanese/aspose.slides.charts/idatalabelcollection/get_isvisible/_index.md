---
title: get_IsVisible()
second_title: Aspose.Slides for C++ API リファレンス
description: False は、データラベルがデフォルトで表示されないことを意味します（そのため DefaultDataLabelFormat プロパティのすべての Show*-flags (ShowValue, ...) は false です）。読み取り専用 bool。
type: docs
weight: 27
url: /ja/aspose.slides.charts/idatalabelcollection/get_isvisible/
---
## IDataLabelCollection::get_IsVisible() メソッド

False は、データラベルがデフォルトで表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-flags (ShowValue, ...) は false です)。読み取り専用 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelCollection::get_IsVisible()=0
```

## 備考

データラベルがデフォルトで表示されている場合、[Hide()](../hide/) メソッドを使用してデフォルトで非表示にできます。ですが、データラベルがデフォルトで表示されていない場合 (IsVisible は false) は、DefaultDataLabelFormat プロパティの Show*-flags (ShowValue, ...) を true に設定することでデータラベルを「表示
デフォルトで」にすることができます。

## 参照

* クラス [IDataLabelCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)