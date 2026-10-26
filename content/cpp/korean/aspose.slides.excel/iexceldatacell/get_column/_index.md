---
title: get_Column()
second_title: Aspose.Slides for C++ API 참조
description: 워크시트에서 셀이 위치한 열의 0부터 시작하는 인덱스를 가져옵니다. 읽기 전용 int32_t.
type: docs
weight: 40
url: /ko/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() 메서드


워크시트에서 셀이 위치한 열의 0부터 시작하는 인덱스를 가져옵니다. 읽기 전용 **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## 비고


예시: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## 참조

* 클래스 [IExcelDataCell](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* 라이브러리 [Aspose.Slides](../../../)