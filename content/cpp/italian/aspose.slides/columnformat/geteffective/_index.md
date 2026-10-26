---
title: GetEffective()
second_title: Aspose.Slides per l'API di riferimento C++
description: Recupera le proprietà di formattazione effective della colonna della tabella con ereditarietà e stili della tabella applicati.
type: docs
weight: 1
url: /it/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() metodo


Recupera le proprietà di formattazione effective della colonna della tabella con ereditarietà e stili della tabella applicati.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```


### Valore di ritorno

Un [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## Osservazioni



Questo esempio dimostra come ottenere il formato di riempimento effective per diverse parti logiche della tabella. Si noti che la formattazione delle celle ha sempre priorità più alta rispetto alla formattazione delle righe, le righe hanno priorità più alta rispetto alle colonne, le colonne hanno priorità più alta rispetto all'intera tabella. Pertanto, le proprietà CellFormatEffectiveData vengono sempre utilizzate per disegnare la tabella. Il codice seguente è solo un esempio di API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Output e confronto
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Classe [ColumnFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)