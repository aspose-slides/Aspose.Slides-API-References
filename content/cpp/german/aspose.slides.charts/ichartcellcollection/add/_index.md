---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine neue Zelle zur Sammlung hinzu.
type: docs
weight: 53
url: /de/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) Methode

Fügt eine neue Zelle zur Sammlung hinzu.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Neue Zelle, die hinzugefügt werden soll. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) Methode

Erstellt [IChartDataCell](../../ichartdatacell/) aus dem angegebenen Wert und fügt es zur Sammlung hinzu.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Der Wert. |

## Bemerkungen

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und legt dort alle Werte ab. Wenn Sie [IChartDataWorkbook](../../ichartdataworkbook/) verwenden, um [Cell](../../../aspose.slides/cell/)-Werte hinzuzufügen oder zu bearbeiten, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden. Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden können, darf 16711680 nicht überschreiten.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [IChartCellCollection](../)
* Klasse [Object](../../../system/object/)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)