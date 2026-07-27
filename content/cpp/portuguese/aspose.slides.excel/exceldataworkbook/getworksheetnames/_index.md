---
title: GetWorksheetNames()
second_title: Aspose.Slides para C++ Referência da API
description: Recupera os nomes de todas as planilhas contidas na pasta de trabalho do Excel.
type: docs
weight: 53
url: /pt/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() método

Recupera os nomes de todas as planilhas contidas na pasta de trabalho [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```

### Valor de Retorno

Uma lista de nomes de planilhas

## Observações



Exemplo: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IList](../../../system.collections.generic/ilist/)
* Classe [String](../../../system/string/)
* Classe [ExcelDataWorkbook](../)
* Espaço de nomes [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)