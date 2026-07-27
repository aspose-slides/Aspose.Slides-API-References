---
title: get_Row()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o índice baseado em zero da linha na planilha onde a célula está localizada. Somente leitura int32_t.
type: docs
weight: 27
url: /pt/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() método


Obtém o índice baseado em zero da linha na planilha onde a célula está localizada. Somente leitura **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Ver Também

* Classe [ExcelDataCell](../)
* Espaço de nomes [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)