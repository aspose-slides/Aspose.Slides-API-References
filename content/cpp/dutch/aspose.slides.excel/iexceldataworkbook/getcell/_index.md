---
title: GetCell()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een cel op uit het opgegeven werkblad met behulp van de index en de celcoördinaten.
type: docs
weight: 14
url: /nl/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) method

Haalt een cel op uit het opgegeven werkblad met behulp van de index en de celcoördinaten.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Zero-based index of the worksheet. |
| row | **int32_t** | Zero-based row index of the cell. |
| column | **int32_t** | Zero-based column index of the cell. |

### Retourwaarde

De cel op de opgegeven locatie.

## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) method

Haalt een cel op uit het opgegeven werkblad met behulp van de naam en de celcoördinaten.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet. |
| row | **int32_t** | Zero-based row index of the cell. |
| column | **int32_t** | Zero-based column index of the cell. |

### Retourwaarde

De cel op de opgegeven locatie.

## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) method

Haalt een cel op uit het opgegeven werkblad met behulp van de index en een Excel-achtige celnaam (bijv. "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Zero-based index of the worksheet. |
| cellName | [System::String](../../../system/string/) | The Excel-style cell reference (e.g., "A1", "C5"). |

### Retourwaarde

De cel op de opgegeven locatie.

## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) method

Haalt een cel op uit het opgegeven werkblad met behulp van een Excel-achtige celnaam (bijv. "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet. |
| cellName | [System::String](../../../system/string/) | The Excel-style cell reference (e.g., "A1", "C5"). |

### Retourwaarde

De cel op de opgegeven locatie.

## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [IExcelDataWorkbook](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)