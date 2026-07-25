---
title: AddTable()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 469
url: /ja/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) メソッド

新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | テーブルの x 座標（ポイント単位）。 |
| y | **float** | テーブルの y 座標（ポイント単位）。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | テーブルの列幅を表す double の配列（ポイント単位）。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | テーブルの行高さを表す double の配列（ポイント単位）。 |

### 戻り値

新しく作成された[ITable](../../itable/)。

## 備考

次の例は、PowerPoint [Presentation](../../presentation/)でテーブルを追加する方法を示しています。 
```cpp
// PPTX ファイルを表す Presentation クラスのインスタンスを作成します
auto pres = System::MakeObject<Presentation>();
// 最初のスライドにアクセスします
auto slide = pres->get_Slides()->idx_get(0);
// 列幅と行高さを指定して列と行を定義します
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// スライドにテーブル シェイプを追加します
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// 各セルの枠線フォーマットを設定します
for (int32_t row = 0; row < table->get_Rows()->get_Count(); row++)
{
    auto currentRow = table->get_Rows()->idx_get(row);
    for (int32_t col = 0; col < currentRow->get_Count(); col++)
    {
        auto cell = currentRow->idx_get(col);
        auto cellFormat = cell->get_CellFormat();
        cellFormat->get_BorderTop()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderTop()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderTop()->set_Width(5);
        cellFormat->get_BorderBottom()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderBottom()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderBottom()->set_Width(5);
        cellFormat->get_BorderLeft()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderLeft()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderLeft()->set_Width(5);
        cellFormat->get_BorderRight()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderRight()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderRight()->set_Width(5);
    }
}

// 行 1 のセル 1 と 2 を結合します
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// 結合されたセルにテキストを追加します
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// PPTX をディスクに保存します
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ITable](../../itable/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)