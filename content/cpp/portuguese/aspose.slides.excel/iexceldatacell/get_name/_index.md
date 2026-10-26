---
title: get_Name()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém o nome da célula de dados do gráfico. Somente leitura System::String."
type: docs
weight: 14
url: /pt/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() método


Obtém o nome da célula de dados do gráfico. Somente leitura [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Veja Também

* Classe [String](../../../system/string/)
* Classe [IExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)