---
title: get_Value()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Excel 셀에 포함된 값을 가져옵니다.
type: docs
weight: 1
url: /ko/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() 메서드


해당 [Excel](../../) 셀에 포함된 값을 가져옵니다.

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## 비고


예: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [ExcelDataCell](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* 라이브러리 [Aspose.Slides](../../../)