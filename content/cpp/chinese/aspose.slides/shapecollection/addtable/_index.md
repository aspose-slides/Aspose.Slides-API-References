---
title: AddTable()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新表并将其添加到形状集合的末尾。
type: docs
weight: 469
url: /zh/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 方法

创建一个新表并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 表的 x 坐标，单位为点。 |
| y | **float** | 表的 y 坐标，单位为点。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 表示表格列宽的 double 数组，单位为点。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 表示表格行高的 double 数组，单位为点。 |

### 返回值

新创建的 [ITable](../../itable/)。

## 备注

下面的示例展示了如何在 PowerPoint [Presentation](../../presentation/) 中添加表格。

```cpp
// 实例化表示 PPTX 文件的 Presentation 类
auto pres = System::MakeObject<Presentation>();
// 获取第一张幻灯片
auto slide = pres->get_Slides()->idx_get(0);
// 定义列宽和行高
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// 向幻灯片添加表格形状
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// 为每个单元格设置边框格式
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

// 合并第1行的第1个和第2个单元格
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// 向合并的单元格添加文本
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// 将 PPTX 保存到磁盘
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ITable](../../itable/)
* 类 [ShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)