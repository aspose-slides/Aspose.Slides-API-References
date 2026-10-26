---
title: GetCell()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Index und ihrer Zellkoordinaten ab.
type: docs
weight: 14
url: /de/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) Methode

Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Index und ihrer Zellkoordinaten ab.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Nullbasierter Index des Arbeitsblatts. |
| row | **int32_t** | Nullbasierter Zeilenindex der Zelle. |
| column | **int32_t** | Nullbasierter Spaltenindex der Zelle. |

### Rückgabewert

Die Zelle am angegebenen Ort.

## Anmerkungen



Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) Methode

Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Namens und ihrer Zellkoordinaten ab.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts. |
| row | **int32_t** | Nullbasierter Zeilenindex der Zelle. |
| column | **int32_t** | Nullbasierter Spaltenindex der Zelle. |

### Rückgabewert

Die Zelle am angegebenen Ort.

## Anmerkungen



Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) Methode

Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Index und des Excel-artigen Zellnamens (z. B. "B2") ab.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Nullbasierter Index des Arbeitsblatts. |
| cellName | [System::String](../../../system/string/) | Der Excel-artige Zellbezug (z. B. "A1", "C5"). |

### Rückgabewert

Die Zelle am angegebenen Ort.

## Anmerkungen



Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) Methode

Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand des Excel-artigen Zellnamens (z. B. "B2") ab.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts. |
| cellName | [System::String](../../../system/string/) | Der Excel-artige Zellbezug (z. B. "A1", "C5"). |

### Rückgabewert

Die Zelle am angegebenen Ort.

## Anmerkungen



Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IExcelDataCell](../../iexceldatacell/)
* Klasse [IExcelDataWorkbook](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)