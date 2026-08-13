---
title: GetCell()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 워크시트에서 인덱스와 셀 좌표를 사용하여 셀을 가져옵니다.
type: docs
weight: 27
url: /ko/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) 메서드

지정된 워크시트에서 인덱스와 셀 좌표를 사용하여 셀을 가져옵니다.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트의 0 기반 인덱스. |
| row | **int32_t** | 셀의 0 기반 행 인덱스. |
| column | **int32_t** | 셀의 0 기반 열 인덱스. |

### 반환값

지정된 위치에 있는 셀.

## 비고

예:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) 메서드

지정된 워크시트에서 이름과 셀 좌표를 사용하여 셀을 가져옵니다.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 워크시트의 이름. |
| row | **int32_t** | 셀의 0 기반 행 인덱스. |
| column | **int32_t** | 셀의 0 기반 열 인덱스. |

### 반환값

지정된 위치에 있는 셀.

## 비고

예:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) 메서드

지정된 워크시트에서 인덱스와 Excel 형식 셀 이름(예: "B2")을 사용하여 셀을 가져옵니다.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트의 0 기반 인덱스. |
| cellName | [System::String](../../../system/string/) | Excel 형식 셀 참조(예: "A1", "C5"). |

### 반환값

지정된 위치에 있는 셀.

## 비고

예:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) 메서드

지정된 워크시트에서 Excel 형식 셀 이름(예: "B2")을 사용하여 셀을 가져옵니다.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 워크시트의 이름. |
| cellName | [System::String](../../../system/string/) | Excel 형식 셀 참조(예: "A1", "C5"). |

### 반환값

지정된 위치에 있는 셀.

## 비고

예:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IExcelDataCell](../../iexceldatacell/)
* 클래스 [ExcelDataWorkbook](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::Excel](../../)
* 라이브러리 [Aspose.Slides](../../../)