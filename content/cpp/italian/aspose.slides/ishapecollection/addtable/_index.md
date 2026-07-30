---
title: AddTable()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova tabella e la aggiunge alla fine della raccolta di forme.
type: docs
weight: 430
url: /it/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metodo

Crea una nuova tabella e la aggiunge alla fine della raccolta di forme.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x della tabella, in punti. |
| y | **float** | La coordinata y della tabella, in punti. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un array di double che rappresenta le larghezze delle colonne della tabella, in punti. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un array di double che rappresenta le altezze delle righe della tabella, in punti. |

### Valore di ritorno

Il [ITable](../../itable/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ITable](../../itable/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)