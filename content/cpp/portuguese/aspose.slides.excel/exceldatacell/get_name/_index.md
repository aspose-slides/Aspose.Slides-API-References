---
title: get_Name()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o nome da célula de dados do gráfico.
type: docs
weight: 14
url: /pt/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() método

Obtém o nome da célula de dados do gráfico.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
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
* Classe [ExcelDataCell](../)
* Espaço de nomes [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)