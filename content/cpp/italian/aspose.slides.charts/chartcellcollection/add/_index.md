---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova cella alla collezione.
type: docs
weight: 53
url: /it/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metodo

Aggiunge una nuova cella alla collezione.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nuova cella da aggiungere. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) metodo

Crea [ChartDataCell](../../chartdatacell/) dal valore specificato e lo aggiunge alla collezione.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Il valore. |
## Osservazioni

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi inserisce tutti i valori. Se utilizzi [ChartDataWorkbook](../../chartdataworkbook/) per aggiungere o modificare i valori [Cell](../../../aspose.slides/cell/), assicurati di non utilizzare questo foglio di lavoro. Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartCellCollection](../)
* Classe [Object](../../../system/object/)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)