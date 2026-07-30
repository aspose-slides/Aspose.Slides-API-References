---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Se la categoria esiste nella collezione, la restituisce. Altrimenti crea una nuova categoria di grafico da IChartDataCell e la aggiunge alla collezione.
type: docs
weight: 92
url: /it/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metodo


Se la categoria esiste nella collezione, la restituisce. Altrimenti crea una nuova categoria di grafico da [IChartDataCell](../../ichartdatacell/) e la aggiunge alla collezione.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) utilizzato per creare la categoria di grafico. |

### Valore di ritorno

Categoria aggiunta o già esistente.



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metodo


Crea un nuovo [ChartCategory](../../chartcategory/) dal valore e lo aggiunge alla collezione.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Il valore. |

### Valore di ritorno

Aggiunto [IChartCategory](../../ichartcategory/).
## Osservazioni



Questo metodo aggiunge un foglio di lavoro con il nome AUTO_DATA e vi inserisce tutti i valori. Se utilizzi [ChartDataWorkbook](../../chartdataworkbook/) per aggiungere o modificare i valori delle celle, assicurati di non utilizzare questo foglio di lavoro. Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680



## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategory](../../ichartcategory/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartCategoryCollection](../)
* Classe [Object](../../../system/object/)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)