---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Sammlung eine neue Zelle hinzu.
type: docs
weight: 53
url: /de/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) Methode


Fügt der Sammlung eine neue Zelle hinzu.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Neue Zelle, die hinzugefügt werden soll. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) Methode


Erstellt [ChartDataCell](../../chartdatacell/) aus dem angegebenen Wert und fügt es der Sammlung hinzu.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Der Wert. |
## Anmerkungen



Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und legt dort alle Werte an. Wenn Sie [ChartDataWorkbook](../../chartdataworkbook/) verwenden, um [Cell](../../../aspose.slides/cell/)-Werte hinzuzufügen oder zu bearbeiten, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht verwenden. Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden können, darf 16711680 nicht überschreiten.



## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [ChartCellCollection](../)
* Klasse [Object](../../../system/object/)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)