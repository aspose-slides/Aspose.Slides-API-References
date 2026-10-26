---
title: get_Name()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "차트 데이터 셀의 이름을 가져옵니다. 읽기 전용 System::String."
type: docs
weight: 14
url: /ko/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() 메서드


차트 데이터 셀의 이름을 가져옵니다. 읽기 전용 [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## 비고


예시: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IExcelDataCell](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* 라이브러리 [Aspose.Slides](../../../)