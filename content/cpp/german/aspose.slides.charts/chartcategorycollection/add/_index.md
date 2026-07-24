---
title: Add()
second_title: Aspose.Slides für C++ API Referenz
description: Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus IChartDataCell erstellt und zur Sammlung hinzugefügt.
type: docs
weight: 92
url: /de/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) Methode

Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus [IChartDataCell](../../ichartdatacell/) erstellt und zur Sammlung hinzugefügt.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) wird verwendet, um eine Diagrammkategorie zu erstellen. |

### Rückgabewert

Hinzugefügte oder vorhandene Kategorie.

## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) Methode

Erstellt ein neues [ChartCategory](../../chartcategory/) aus dem Wert und fügt es der Sammlung hinzu.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Der Wert. |

### Rückgabewert

Hinzugefügtes [IChartCategory](../../ichartcategory/).

## Hinweise

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und fügt dort alle Werte ein. Wenn Sie [ChartDataWorkbook](../../chartdataworkbook/) zum Hinzufügen oder Bearbeiten von Zellenwerten verwenden, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden. Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden, darf 16711680 nicht überschreiten.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartCategory](../../ichartcategory/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [ChartCategoryCollection](../)
* Klasse [Object](../../../system/object/)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)