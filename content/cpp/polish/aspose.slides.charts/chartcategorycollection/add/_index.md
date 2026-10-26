---
title: Add()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Jeśli kategoria istnieje w kolekcji, zwróć ją. W przeciwnym razie tworzona jest nowa kategoria wykresu z IChartDataCell i dodawana do kolekcji.
type: docs
weight: 92
url: /pl/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metoda

Jeśli kategoria istnieje w kolekcji, zwróć ją. W przeciwnym razie tworzy nową kategorię wykresu z [IChartDataCell](../../ichartdatacell/) i dodaje ją do kolekcji.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) używany do tworzenia kategorii wykresu. |

### Wartość zwracana

Dodana lub istniejąca kategoria.

## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metoda

Tworzy nowy [ChartCategory](../../chartcategory/) z wartości i dodaje go do kolekcji.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Wartość. |

### Wartość zwracana

Dodane [IChartCategory](../../ichartcategory/).

## Uwagi

Ta metoda dodaje arkusz kalkulacyjny o nazwie AUTO_DATA i dodaje tam wszystkie wartości. Jeśli używasz [ChartDataWorkbook](../../chartdataworkbook/) do dodawania lub edytowania wartości komórek, upewnij się, że nie używasz tego arkusza. Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekraczać 16711680

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartCategory](../../ichartcategory/)
* Klasa [IChartDataCell](../../ichartdatacell/)
* Klasa [ChartCategoryCollection](../)
* Klasa [Object](../../../system/object/)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)