---
title: get_ShowCategoryName()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたチャートのデータラベルのカテゴリ名表示動作を表します。True はチャート上のデータラベルのカテゴリ名を表示し、False は非表示にします。bool を読み取り専用です。
type: docs
weight: 144
url: /ja/aspose.slides.charts/idatalabelformat/get_showcategoryname/
---
## IDataLabelFormat::get_ShowCategoryName() メソッド

指定されたチャートのデータラベルのカテゴリ名の表示動作を表します。True はチャート上のデータラベルのカテゴリ名を表示します。False は非表示にします。読み取り **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowCategoryName()=0
```

## 備考

この [DataLabelFormat](../../datalabelformat/) オブジェクトの親が [DataLabelCollection](../../datalabelcollection/) データラベルのコレクションである場合、このプロパティは [DataLabelCollection](../../datalabelcollection/) コレクション内の新しいデータラベルに対する ShowCategoryName プロパティの既定値を取得または設定します。値を設定すると、この値は [DataLabelCollection](../../datalabelcollection/) コレクション内のすべてのデータラベルの ShowCategoryName プロパティにも設定されます（例: "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" により、すべての DataLabels[i].ShowCategoryName が val と等しくなります）。

## 参照

* クラス [IDataLabelFormat](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)