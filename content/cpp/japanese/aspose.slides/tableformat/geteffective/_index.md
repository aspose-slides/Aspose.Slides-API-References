---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承とテーブルスタイルが適用された実効テーブル書式設定プロパティを取得します。
type: docs
weight: 40
url: /ja/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() メソッド

継承とテーブルスタイルが適用された、実効テーブル書式設定プロパティを取得します。

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```

### 戻り値

A [ITableFormatEffectiveData](../../itableformateffectivedata/).

## 備考

この例では、異なるテーブル論理パーツに対する実効塗りつぶし書式の取得方法を示しています。セルの書式設定は常に行の書式設定よりも優先度が高く、行は列よりも、列はテーブル全体よりも優先されます。そのため、最終的にテーブルを描画する際には常に CellFormatEffectiveData のプロパティが使用されます。以下のコードは API の例です。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ITableFormatEffectiveData](../../itableformateffectivedata/)
* クラス [TableFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)