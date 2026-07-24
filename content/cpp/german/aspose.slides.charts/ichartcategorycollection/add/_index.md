---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus IChartDataCell erstellt und zur Sammlung hinzugefügt.
type: docs
weight: 53
url: /de/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) Methode

Wenn die Kategorie in der Sammlung bereits existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus [IChartDataCell](../../ichartdatacell/) erstellt und zur Sammlung hinzugefügt.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) verwendet, um die Diagrammkategorie zu erstellen. |

### Rückgabewert

Hinzugefügte oder vorhandene Kategorie.

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) Methode

Erstellt eine neue [IChartCategory](../../ichartcategory/) aus dem Wert und fügt sie der Sammlung hinzu.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Der Wert. |

### Rückgabewert

Hinzugefügtes [IChartCategory](../../ichartcategory/).

## Anmerkungen

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und fügt dort alle Werte ein. Wenn Sie [IChartDataWorkbook](../../ichartdataworkbook/) verwenden, um Zellenwerte hinzuzufügen oder zu bearbeiten, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden. Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden darf, darf 16711680 nicht überschreiten.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartCategory](../../ichartcategory/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [IChartCategoryCollection](../)
* Klasse [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)