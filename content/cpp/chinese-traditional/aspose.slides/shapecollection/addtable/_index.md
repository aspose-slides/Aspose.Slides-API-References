---
title: AddTable()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新表格，並將它加入形狀集合的末端。
type: docs
weight: 469
url: /zh-hant/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 方法

建立一個新表格，並將它加入形狀集合的末端。

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 表格的 x 坐標，單位為點。 |
| y | **float** | 表格的 y 坐標，單位為點。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一個 double 陣列，表示表格欄位的寬度，單位為點。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一個 double 陣列，表示表格列的高度，單位為點。 |

### 回傳值

新建立的 [ITable](../../itable/)。

## 備註

以下範例說明如何在 PowerPoint [Presentation](../../presentation/) 中新增表格。

```cpp
// 建立代表 PPTX 檔案的 Presentation 類別實例
auto pres = System::MakeObject<Presentation>();
// 取得第一張投影片
auto slide = pres->get_Slides()->idx_get(0);
// 定義欄寬與列高
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// 將表格形狀新增至投影片
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// 設定每個儲存格的框線格式
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

// 合併第 1 列的第 1 與第 2 個儲存格
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// 為合併的儲存格新增文字
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// 將 PPTX 儲存至磁碟
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [ITable](../../itable/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)