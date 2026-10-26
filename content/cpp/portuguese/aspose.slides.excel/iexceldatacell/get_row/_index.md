---
title: get_Row()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém o índice baseado em zero da linha na planilha onde a célula está localizada. Somente leitura int32_t.
type: docs
weight: 27
url: /pt/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() method

Obtém o índice baseado em zero da linha na planilha onde a célula está localizada. Somente leitura **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## Veja Também

* Classe [IExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)