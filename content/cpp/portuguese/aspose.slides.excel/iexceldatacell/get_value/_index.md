---
title: get_Value()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém o valor contido na célula Excel. Somente leitura System::Object."
type: docs
weight: 1
url: /pt/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() método

Obtém o valor contido na célula [Excel](../../). Somente leitura [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Observações

Exemplo:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Ver também

* Definição de tipo [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [IExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)