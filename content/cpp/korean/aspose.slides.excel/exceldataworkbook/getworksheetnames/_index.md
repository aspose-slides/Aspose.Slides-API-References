---
title: GetWorksheetNames()
second_title: Aspose.Slides for C++ API 참조
description: Excel 워크북에 포함된 모든 워크시트의 이름을 검색합니다.
type: docs
weight: 53
url: /ko/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() 메서드

[Excel](../../) 워크북에 포함된 모든 워크시트의 이름을 검색합니다.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```

### 반환 값

워크시트 이름 목록

## 비고



예제: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IList](../../../system.collections.generic/ilist/)
* 클래스 [String](../../../system/string/)
* 클래스 [ExcelDataWorkbook](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* 라이브러리 [Aspose.Slides](../../../)