---
title: GetWorksheetNames()
second_title: Aspose.Slides for C++ API 참조
description: Excel 워크북에 포함된 모든 워크시트 이름을 가져옵니다.
type: docs
weight: 40
url: /ko/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() 메서드


[Excel](../../) 워크북에 포함된 모든 워크시트의 이름을 가져옵니다.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### 반환 값

워크시트 이름 목록
## 비고



예시: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IList](../../../system.collections.generic/ilist/)
* 클래스 [String](../../../system/string/)
* 클래스 [IExcelDataWorkbook](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)