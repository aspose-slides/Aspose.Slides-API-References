---
title: GetCell()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal een cel op uit het opgegeven werkblad met behulp van de index en celcoördinaten.
type: docs
weight: 27
url: /nl/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) methode


Haal een cel op uit het opgegeven werkblad met behulp van de index en celcoördinaten.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Nulgebaseerde index van het werkblad. |
| row | **int32_t** | Nulgebaseerde rij-index van de cel. |
| column | **int32_t** | Nulgebaseerde kolom-index van de cel. |

### Retourwaarde

De cel op de opgegeven locatie.

## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) methode


Haal een cel op uit het opgegeven werkblad met behulp van de naam en celcoördinaten.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad. |
| row | **int32_t** | Nulgebaseerde rij-index van de cel. |
| column | **int32_t** | Nulgebaseerde kolom-index van de cel. |

### Retourwaarde

De cel op de opgegeven locatie.

## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) methode


Haal een cel op uit het opgegeven werkblad met behulp van de index en een Excel-achtige celnaam (bijv. "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Nulgebaseerde index van het werkblad. |
| cellName | [System::String](../../../system/string/) | De Excel-achtige celreferentie (bijv. "A1", "C5"). |

### Retourwaarde

De cel op de opgegeven locatie.

## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) methode


Haal een cel op uit het opgegeven werkblad met behulp van een Excel-achtige celnaam (bijv. "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad. |
| cellName | [System::String](../../../system/string/) | De Excel-achtige celreferentie (bijv. "A1", "C5"). |

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
* Klasse [IExcelDataCell](../../iexceldatacell/)
* Klasse [ExcelDataWorkbook](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)