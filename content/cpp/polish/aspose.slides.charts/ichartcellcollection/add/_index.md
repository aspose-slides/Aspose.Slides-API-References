---
title: Add()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dodaj nową komórkę do kolekcji.
type: docs
weight: 53
url: /pl/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metoda

Dodaj nową komórkę do kolekcji.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nowa komórka do dodania. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) metoda

Tworzy [IChartDataCell](../../ichartdatacell/) z określonej wartości i dodaje ją do kolekcji.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Wartość. |

## Uwagi

Ta metoda dodaje arkusz kalkulacyjny o nazwie AUTO_DATA i dodaje do niego wszystkie wartości. Jeśli używasz [IChartDataWorkbook](../../ichartdataworkbook/) do dodawania lub edytowania wartości [Cell](../../../aspose.slides/cell/), upewnij się, że nie używasz tego arkusza. Maksymalna liczba wartości dodawanych za pomocą tej metody nie może przekroczyć 16711680

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartDataCell](../../ichartdatacell/)
* Klasa [IChartCellCollection](../)
* Klasa [Object](../../../system/object/)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)