---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective table cell formatting properties with inheritance and table styles applied.
type: docs
weight: 118
url: /aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() method


Gets effective table cell formatting properties with inheritance and table styles applied.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```


### Return Value

A [ICellFormatEffectiveData](../../icellformateffectivedata/).
## Remarks



This example demonstrates getting effective fill format for different table logic parts. Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table. So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Output and comparison
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Class [CellFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)