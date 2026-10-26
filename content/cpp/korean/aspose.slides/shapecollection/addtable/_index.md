---
title: AddTable()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 테이블을 생성하고 이를 Shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 469
url: /ko/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method

새 테이블을 만들고 이를 Shape 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 테이블의 x 좌표이며, 포인트 단위입니다. |
| y | **float** | 테이블의 y 좌표이며, 포인트 단위입니다. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 테이블 열의 너비를 나타내는 double 배열이며, 포인트 단위입니다. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 테이블 행의 높이를 나타내는 double 배열이며, 포인트 단위입니다. |

### 반환 값

새로 생성된 [ITable](../../itable/).

## 비고

다음 예제에서는 PowerPoint [Presentation](../../presentation/)에서 테이블을 추가하는 방법을 보여줍니다.
```cpp
// PPTX 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>();
// 첫 번째 슬라이드에 접근합니다
auto slide = pres->get_Slides()->idx_get(0);
// 열 너비와 행 높이를 정의합니다
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// 슬라이드에 테이블 형태를 추가합니다
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// 각 셀의 테두리 형식을 설정합니다
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

// 첫 번째 행의 셀 1과 2를 병합합니다
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// 병합된 셀에 텍스트를 추가합니다
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// PPTX 파일을 디스크에 저장합니다
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)