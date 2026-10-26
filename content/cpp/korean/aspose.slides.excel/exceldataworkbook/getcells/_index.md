---
title: GetCells()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 수식과 일치하는 셀을 워크북에서 가져옵니다.
type: docs
weight: 14
url: /ko/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) method

지정된 수식과 일치하는 셀을 워크북에서 가져옵니다.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 대상 셀을 식별하는 데 사용되는 수식 또는 범위 식(예: "Sheet1!A1:B3"). |
| skipHiddenCells | **bool** | **true**인 경우, 숨겨진 셀(예: 숨겨진 행이나 열에 있는 셀)은 결과에서 제외됩니다. |

## 반환 값

지정된 수식과 일치하는 셀의 읽기 전용 리스트입니다.

## 비고



예제:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [String](../../../system/string/)
* Class [ExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)