---
title: GetWorksheetNames()
second_title: Referência da API Aspose.Slides para C++
description: Recupera os nomes de todas as planilhas contidas na pasta de trabalho do Excel.
type: docs
weight: 40
url: /pt/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() método


Recupera os nomes de todas as planilhas contidas na pasta de trabalho [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IList](../../../system.collections.generic/ilist/)
* Classe [String](../../../system/string/)
* Classe [IExcelDataWorkbook](../)
* Espaço de nomes [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)