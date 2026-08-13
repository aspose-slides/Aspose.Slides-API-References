---
title: GetEffective()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상속 및 테이블 스타일이 적용된 실제 테이블 열 서식 속성을 가져옵니다.
type: docs
weight: 1
url: /ko/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() 메서드

Gets effective table column formatting properties with inheritance and table styles applied.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### 반환값

A [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## 비고

This example demonstrates getting effective fill format for different table logic parts. Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table. So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// 출력 및 비교
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Class [ColumnFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)