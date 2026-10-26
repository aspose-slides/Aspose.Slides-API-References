---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承とテーブルスタイルが適用された、実効的なテーブルセルの書式設定プロパティを取得します。
type: docs
weight: 118
url: /ja/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() メソッド


継承およびテーブルスタイルが適用された、実効的なテーブルセルの書式設定プロパティを取得します。

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```


### 戻り値

A [ICellFormatEffectiveData](../../icellformateffectivedata/).

## 備考



この例は、さまざまなテーブルの論理パーツに対する実効的な塗りつぶし形式の取得方法を示しています。セルの書式設定は常に行の書式設定よりも優先され、行は列よりも優先され、列はテーブル全体よりも優先されることに注意してください。したがって最終的に CellFormatEffectiveData のプロパティがテーブルの描画に使用されます。以下のコードは API の例示にすぎません。 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ICellFormatEffectiveData](../../icellformateffectivedata/)
* クラス [CellFormat](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)