---
title: GetEffective()
second_title: Aspose.Slides for C++ API 참조
description: 상속 및 테이블 스타일이 적용된 효과적인 테이블 서식 속성을 가져옵니다.
type: docs
weight: 40
url: /ko/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() 메서드


상속 및 테이블 스타일이 적용된 효과적인 테이블 서식 속성을 가져옵니다.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### 반환값

A [ITableFormatEffectiveData](../../itableformateffectivedata/).
## 비고



이 예제는 다양한 테이블 논리 부분에 대한 효과적인 채우기 서식을 가져오는 방법을 보여줍니다. 셀 서식은 항상 행 서식보다 높은 우선순위를 가지고, 행은 열보다, 열은 전체 테이블보다 높은 우선순위를 가집니다. 따라서 최종적으로 CellFormatEffectiveData 속성이 테이블을 그릴 때 항상 사용됩니다. 다음 코드는 API 사용 예시일 뿐입니다. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ITableFormatEffectiveData](../../itableformateffectivedata/)
* 클래스 [TableFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)