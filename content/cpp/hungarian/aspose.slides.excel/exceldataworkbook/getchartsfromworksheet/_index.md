---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API referencia
description: Lekéri egy szótárat, amely tartalmazza a megadott munkalapon található összes diagram indexeit és neveit egy Excel munkafüzetben.
type: docs
weight: 40
url: /hu/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) metódus


Lekéri egy szótárt, amely tartalmazza az adott [Excel](../../) munkafüzet meghatározott munkalapján található összes diagram indexeit és neveit.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve, amelyen a diagramokat keresni kell. |

### Visszatérési érték

Egy szótár, ahol a kulcs a diagram indexe, az érték pedig a diagram neve.

## Megjegyzések



Példa: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IDictionary](../../../system.collections.generic/idictionary/)
* Osztály [String](../../../system/string/)
* Osztály [ExcelDataWorkbook](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)