---
title: InsertTable()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova tabella e la inserisce nella raccolta di forme all'indice specificato.
type: docs
weight: 482
url: /it/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Crea una nuova tabella e la inserisce nella raccolta di forme all'indice specificato.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire la tabella. |
| x | **float** | La coordinata x della tabella, in punti. |
| y | **float** | La coordinata y della tabella, in punti. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un array di double che rappresenta le larghezze delle colonne della tabella\\u2019, in punti. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un array di double che rappresenta le altezze delle righe della tabella\\u2019, in punti. |

### Valore di ritorno

Il [ITable](../../itable/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ITable](../../itable/)
* Classe [ShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)