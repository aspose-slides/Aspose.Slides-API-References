---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Se la categoria esiste nella collezione, la restituisce. Altrimenti crea una nuova categoria del grafico da IChartDataCell e la aggiunge alla collezione.
type: docs
weight: 53
url: /it/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metodo

Se la categoria esiste nella collezione, la restituisce. Altrimenti crea una nuova categoria del grafico da [IChartDataCell](../../ichartdatacell/) e la aggiunge alla collezione.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) utilizzato per creare la categoria del grafico. |

### Valore di ritorno

Categoria aggiunta o esistente.

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metodo

Crea un nuovo [IChartCategory](../../ichartcategory/) dal valore e lo aggiunge alla collezione.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Il valore. |

### Valore di ritorno

Aggiunto [IChartCategory](../../ichartcategory/).

## Osservazioni

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi aggiunge tutti i valori. Se utilizzi [IChartDataWorkbook](../../ichartdataworkbook/) per aggiungere o modificare i valori delle celle, assicurati di non utilizzare questo foglio di lavoro. Il numero massimo di valori aggiunti utilizzando questo metodo non deve superare 16711680

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategory](../../ichartcategory/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartCategoryCollection](../)
* Classe [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)