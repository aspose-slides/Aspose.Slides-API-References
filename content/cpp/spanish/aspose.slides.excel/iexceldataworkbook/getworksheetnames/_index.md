---
title: GetWorksheetNames()
second_title: Referencia de la API de Aspose.Slides para C++
description: Recupera los nombres de todas las hojas de cálculo contenidas en el libro de trabajo de Excel.
type: docs
weight: 40
url: /es/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() method


Recupera los nombres de todas las hojas de cálculo contenidas en el libro de trabajo [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### Valor de retorno

Una lista de nombres de hojas de cálculo
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IList](../../../system.collections.generic/ilist/)
* Clase [String](../../../system/string/)
* Clase [IExcelDataWorkbook](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)