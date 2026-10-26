---
title: GetCells()
second_title: Aspose.Slides for C++ API 참조
description: 워크북에서 지정된 수식과 일치하는 셀 컬렉션을 가져옵니다.
type: docs
weight: 1
url: /ko/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) 메서드

지정된 수식과 일치하는 워크북의 셀 컬렉션을 가져옵니다.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 대상 셀을 식별하는 데 사용되는 수식 또는 범위 식(expression) (예: \"Sheet1!A1:B3\"). |
| skipHiddenCells | **bool** | **true**인 경우, 숨겨진 셀(예: 숨겨진 행이나 열에 있는 셀)은 결과에서 제외됩니다. |

### 반환값

지정된 수식과 일치하는 셀의 읽기 전용 리스트입니다.

## 비고

예시:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* 클래스 [IExcelDataCell](../../iexceldatacell/)
* 클래스 [String](../../../system/string/)
* 클래스 [IExcelDataWorkbook](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)