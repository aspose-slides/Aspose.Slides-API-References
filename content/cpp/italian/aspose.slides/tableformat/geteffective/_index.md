---
title: GetEffective()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene le proprietà di formattazione effective della tabella con ereditarietà e stili di tabella applicati.
type: docs
weight: 40
url: /it/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() metodo


Ottiene le proprietà di formattazione effective della tabella con ereditarietà e stili di tabella applicati.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### Valore di ritorno

Un [ITableFormatEffectiveData](../../itableformateffectivedata/).
## Osservazioni



Questo esempio dimostra come ottenere il formato di riempimento effective per diverse parti logiche della tabella. Si noti che la formattazione delle celle ha sempre priorità più alta rispetto alla formattazione delle righe, le righe hanno priorità più alta rispetto alle colonne, le colonne hanno priorità più alta rispetto all'intera tabella. Quindi, alla fine le proprietà di CellFormatEffectiveData sono sempre utilizzate per disegnare la tabella. Il codice seguente è solo un esempio dell'API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Classe [TableFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)