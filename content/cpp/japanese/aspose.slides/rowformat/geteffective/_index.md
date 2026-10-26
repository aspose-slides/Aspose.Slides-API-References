---
title: GetEffective()
second_title: Aspose.Slides の C++ API リファレンス
description: 継承とテーブルスタイルが適用された有効なテーブル行書式プロパティを取得します。
type: docs
weight: 1
url: /ja/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() メソッド

継承とテーブルスタイルが適用された有効なテーブル行書式プロパティを取得します。

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```

### 戻り値

[IRowFormatEffectiveData](../../irowformateffectivedata/)。

## 備考

この例は、テーブルのさまざまな論理パーツに対して有効な塗りつぶし形式を取得する方法を示しています。セルの書式設定は常に行の書式設定よりも優先度が高く、行は列よりも優先度が高く、列はテーブル全体よりも優先度が高いことに注意してください。そのため、最終的に CellFormatEffectiveData プロパティがテーブルの描画に使用されます。以下のコードは API の例にすぎません。

```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// 出力と比較
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IRowFormatEffectiveData](../../irowformateffectivedata/)
* クラス [RowFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)