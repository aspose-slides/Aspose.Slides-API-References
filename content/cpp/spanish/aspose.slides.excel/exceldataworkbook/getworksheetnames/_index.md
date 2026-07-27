---
title: GetWorksheetNames()
second_title: Referencia de API de Aspose.Slides para C++
description: Recupera los nombres de todas las hojas de cálculo contenidas en el libro de trabajo de Excel.
type: docs
weight: 53
url: /es/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() método


Obtiene los nombres de todas las hojas de cálculo contenidas en el libro de trabajo [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IList](../../../system.collections.generic/ilist/)
* Clase [String](../../../system/string/)
* Clase [ExcelDataWorkbook](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)