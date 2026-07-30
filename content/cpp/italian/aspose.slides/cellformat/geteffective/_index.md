---
title: GetEffective()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene le proprietà di formattazione della cella della tabella effettive con l'ereditarietà e gli stili della tabella applicati.
type: docs
weight: 118
url: /it/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() metodo

Ottiene le proprietà di formattazione della cella della tabella effettive con l'ereditarietà e gli stili della tabella applicati.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### Valore di ritorno

Un [ICellFormatEffectiveData](../../icellformateffectivedata/).

## Osservazioni

Questo esempio dimostra come ottenere il formato di riempimento effettivo per diverse parti logiche della tabella. Si noti che la formattazione della cella ha sempre priorità più alta rispetto alla formattazione della riga, la riga è più alta rispetto alla colonna, la colonna è più alta rispetto all'intera tabella. Quindi, alla fine le proprietà CellFormatEffectiveData vengono sempre utilizzate per disegnare la tabella. Il codice seguente è solo un esempio di API.
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
* Class [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Class [CellFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)