---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective table formatting properties with inheritance and table styles applied.
type: docs
weight: 14
url: /aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() method


Gets effective table formatting properties with inheritance and table styles applied.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### Return Value

A [ITableFormatEffectiveData](../../itableformateffectivedata/).
## Remarks



This example demonstrates getting effective fill format for different table logic parts. Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table. So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Class [TableFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)