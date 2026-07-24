---
title: set_ShowSeriesName()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt einen Boolean, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzugeben. True, um den Seriennamen anzuzeigen. False, um ihn zu verbergen. Schreiben bool.
type: docs
weight: 183
url: /de/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) Methode

Setzt einen Boolean, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzugeben. True, um den Seriennamen anzuzeigen. False, um ihn zu verbergen. Schreiben **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## Bemerkungen

If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;\" cause to all DataLabels[i].ShowSeriesName is equal to val). 

## Siehe auch

* Klasse [IDataLabelFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)