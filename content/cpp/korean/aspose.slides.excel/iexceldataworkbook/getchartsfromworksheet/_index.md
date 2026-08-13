---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 Excel 워크북의 워크시트에 있는 모든 차트의 인덱스와 이름을 포함하는 사전을 검색합니다.
type: docs
weight: 27
url: /ko/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) 메서드

Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an [Excel](../../) workbook.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 차트를 검색할 워크시트의 이름입니다. |

### 반환값

키는 차트 인덱스이고 값은 차트 이름인 사전입니다.

## 비고



예시: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDictionary](../../../system.collections.generic/idictionary/)
* 클래스 [String](../../../system/string/)
* 클래스 [IExcelDataWorkbook](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)