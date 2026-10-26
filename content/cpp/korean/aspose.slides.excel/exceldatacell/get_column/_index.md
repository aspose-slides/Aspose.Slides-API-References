---
title: get_Column()
second_title: Aspose.Slides for C++ API 참조
description: 셀의 위치가 있는 워크시트에서 열의 0부터 시작하는 인덱스를 반환합니다. 읽기 전용 int32_t.
type: docs
weight: 40
url: /ko/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() 메서드


셀의 위치가 있는 워크시트에서 열의 0부터 시작하는 인덱스를 반환합니다. 읽기 전용 **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## 비고


예제: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## 참조

* 클래스 [ExcelDataCell](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* 라이브러리 [Aspose.Slides](../../../)