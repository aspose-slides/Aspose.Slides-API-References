---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova cella alla collezione.
type: docs
weight: 53
url: /it/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metodo

Aggiunge una nuova cella alla collezione.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nuova cella da aggiungere. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) metodo

Crea [IChartDataCell](../../ichartdatacell/) dal valore specificato e lo aggiunge alla collezione.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Il valore. |

## Osservazioni

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e aggiunge tutti i valori lì. Se utilizzi [IChartDataWorkbook](../../ichartdataworkbook/) per aggiungere o modificare i valori [Cell](../../../aspose.slides/cell/), assicurati di non utilizzare questo foglio di lavoro. Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartCellCollection](../)
* Classe [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)