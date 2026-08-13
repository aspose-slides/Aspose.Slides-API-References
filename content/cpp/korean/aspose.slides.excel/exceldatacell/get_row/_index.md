---
title: get_Row()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 셀의 위치한 워크시트에서 행의 0 기반 인덱스를 가져옵니다. 읽기 전용 int32_t.
type: docs
weight: 27
url: /ko/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() 메서드

셀의 위치한 워크시트에서 행의 0 기반 인덱스를 반환합니다. 읽기 전용 **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## 비고

예시: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## 참조

* 클래스 [ExcelDataCell](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* 라이브러리 [Aspose.Slides](../../../)