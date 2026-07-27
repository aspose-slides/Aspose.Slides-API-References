---
title: get_Column()
second_title: Referência da API Aspose.Slides for C++
description: Obtém o índice baseado em zero da coluna na planilha onde a célula está localizada. Somente leitura int32_t.
type: docs
weight: 40
url: /pt/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() método


Obtém o índice baseado em zero da coluna na planilha onde a célula está localizada. Somente leitura **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Ver também

* Classe [ExcelDataCell](../)
* Espaço de nomes [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)