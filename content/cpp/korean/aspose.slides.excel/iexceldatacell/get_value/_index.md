---
title: get_Value()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Excel 셀에 포함된 값을 가져옵니다. 읽기 전용 System::Object."
type: docs
weight: 1
url: /ko/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() 메서드

[Excel](../../) 셀에 포함된 값을 가져옵니다. 읽기 전용 [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## 비고

예시:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [IExcelDataCell](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* 라이브러리 [Aspose.Slides](../../../)