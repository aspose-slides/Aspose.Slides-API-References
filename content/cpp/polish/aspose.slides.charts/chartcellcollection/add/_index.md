---
title: Add()
second_title: Aspose.Slides – dokumentacja API dla C++
description: Dodaj nową komórkę do kolekcji.
type: docs
weight: 53
url: /pl/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metoda

Dodaj nową komórkę do kolekcji.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nowa komórka do dodania. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) metoda

Tworzy [ChartDataCell](../../chartdatacell/) z podanej wartości i dodaje go do kolekcji.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Wartość. |

## Uwagi

Ta metoda dodaje arkusz kalkulacyjny o nazwie AUTO_DATA i dodaje tam wszystkie wartości. Jeśli używasz [ChartDataWorkbook](../../chartdataworkbook/) do dodawania lub edytowania wartości [Cell](../../../aspose.slides/cell/), upewnij się, że nie używasz tego arkusza. Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekroczyć 16711680

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartDataCell](../../ichartdatacell/)
* Klasa [ChartCellCollection](../)
* Klasa [Object](../../../system/object/)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)