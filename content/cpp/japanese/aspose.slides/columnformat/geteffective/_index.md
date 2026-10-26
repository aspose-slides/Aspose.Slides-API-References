---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承とテーブルスタイルが適用された、実効的なテーブル列書式設定プロパティを取得します。
type: docs
weight: 1
url: /ja/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() メソッド


継承とテーブル スタイルが適用された、実効的なテーブル列書式設定プロパティを取得します。

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```


### 戻り値

A [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## 備考



この例は、テーブルのさまざまな論理パーツに対する実効的な塗りつぶし書式の取得方法を示しています。セルの書式設定は常に行の書式設定よりも優先され、行は列よりも優先され、列はテーブル全体よりも優先されることに注意してください。そのため、最終的に CellFormatEffectiveData のプロパティがテーブルの描画に使用されます。以下のコードは API の使用例にすぎません。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// 出力と比較
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* クラス [ColumnFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)