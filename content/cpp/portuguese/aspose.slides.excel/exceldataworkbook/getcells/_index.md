---
title: GetCells()
second_title: Referência da API Aspose.Slides para C++
description: Recupera uma coleção de células da pasta de trabalho que correspondem à fórmula especificada.
type: docs
weight: 14
url: /pt/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) method


Recupera uma coleção de células da pasta de trabalho que correspondem à fórmula especificada.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Uma fórmula ou expressão de intervalo (por exemplo, \"Sheet1!A1:B3\") usada para identificar as células-alvo. |
| skipHiddenCells | **bool** | Se **true**, células ocultas (por exemplo, em linhas ou colunas ocultas) serão excluídas do resultado. |

### Valor de Retorno

Uma lista somente leitura de células que correspondem à fórmula especificada.
## Observações



Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Classe [IExcelDataCell](../../iexceldatacell/)
* Classe [String](../../../system/string/)
* Classe [ExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)