---
title: Add()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Jeśli kategoria istnieje w kolekcji, zwróć ją. W przeciwnym razie tworzy nową kategorię wykresu z IChartDataCell i dodaje ją do kolekcji.
type: docs
weight: 53
url: /pl/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metoda


Jeśli kategoria istnieje w kolekcji, zwróć ją. W przeciwnym razie tworzy nową kategorię wykresu z [IChartDataCell](../../ichartdatacell/) i dodaje ją do kolekcji.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) używany do tworzenia kategorii wykresu. |

### Wartość zwracana

Dodana lub istniejąca kategoria.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metoda


Tworzy nowy [IChartCategory](../../ichartcategory/) z wartości i dodaje go do kolekcji.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Wartość. |

### Wartość zwracana

Dodano [IChartCategory](../../ichartcategory/).
## Uwagi



Ta metoda dodaje arkusz kalkulacyjny o nazwie AUTO_DATA i dodaje tam wszystkie wartości. Jeśli używasz [IChartDataWorkbook](../../ichartdataworkbook/) do dodawania lub edytowania wartości komórek, upewnij się, że nie używasz tego arkusza. Maksymalna liczba wartości dodanych przy użyciu tej metody nie może przekroczyć 16711680



## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)