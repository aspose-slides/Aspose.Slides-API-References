---
title: get_Value()
second_title: Referência da API Aspose.Slides for C++
description: Obtém o valor contido na célula Excel.
type: docs
weight: 1
url: /pt/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() método

Obtém o valor contido na célula [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Observações

Exemplo:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ExcelDataCell](../)
* Espaço de nomes [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)