---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API 참조
description: Excel 워크북의 지정된 워크시트에 있는 모든 차트의 인덱스와 이름을 포함하는 사전을 반환합니다.
type: docs
weight: 40
url: /ko/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) 메서드

[Excel](../../) 워크북의 지정된 워크시트에 있는 모든 차트의 인덱스와 이름을 포함하는 사전을 반환합니다.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 차트를 검색할 워크시트의 이름. |

### 반환값

키가 차트 인덱스이고 값이 차트 이름인 사전.

## 비고

예:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDictionary](../../../system.collections.generic/idictionary/)
* 클래스 [String](../../../system/string/)
* 클래스 [ExcelDataWorkbook](../)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* 라이브러리 [Aspose.Slides](../../../)