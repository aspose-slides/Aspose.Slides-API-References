---
title: IDataLabelCollection
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert eine Serienbeschriftung.
type: docs
weight: 1910
url: /de/net/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection interface

Repräsentiert eine Serienbeschriftung.

```csharp
public interface IDataLabelCollection : IChartComponent, IEnumerable<IDataLabel>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/idatalabelcollection/asichartcomponent) { get; } | Ermöglicht das Abrufen der Basis-IChartComponent-Schnittstelle. Schreibgeschützt[`IChartComponent`](../ichartcomponent) . |
| [AsIEnumerable](../../aspose.slides.charts/idatalabelcollection/asienumerable) { get; } | Ermöglicht das Abrufen der Basis-IEnumerable-Schnittstelle. SchreibgeschütztIEnumerable . |
| [Count](../../aspose.slides.charts/idatalabelcollection/count) { get; } | Ruft die Anzahl aller Datenbeschriftungen in der Sammlung ab. SchreibgeschütztInt32 . |
| [CountOfVisibleDataLabels](../../aspose.slides.charts/idatalabelcollection/countofvisibledatalabels) { get; } | Ruft die Anzahl der sichtbaren Datenbeschriftungen in der Sammlung ab. SchreibgeschütztInt32 . |
| [DefaultDataLabelFormat](../../aspose.slides.charts/idatalabelcollection/defaultdatalabelformat) { get; } | Gibt das Standardformat aller Datenbeschriftungen in der Sammlung zurück. Schreibgeschützt[`IDataLabelFormat`](../idatalabelformat) . |
| [IsVisible](../../aspose.slides.charts/idatalabelcollection/isvisible) { get; } | False bedeutet, dass die Datenbeschriftung standardmäßig nicht sichtbar ist (und daher sind alle Show*-Flags (ShowValue, ...) der DefaultDataLabelFormat-Eigenschaft falsch). Read-onlyBoolean . |
| [Item](../../aspose.slides.charts/idatalabelcollection/item) { get; } | Ruft das Datenlabel für den Datenpunkt mit dem angegebenen Index ab. |
| [ParentSeries](../../aspose.slides.charts/idatalabelcollection/parentseries) { get; } | Gibt übergeordnete Diagrammreihen zurück. Schreibgeschützt[`IChartSeries`](../ichartseries) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Hide](../../aspose.slides.charts/idatalabelcollection/hide)() | Datenbeschriftung standardmäßig unsichtbar machen, indem alle Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf false gesetzt werden. IsVisible ist danach false. |
| [IndexOf](../../aspose.slides.charts/idatalabelcollection/indexof)(IDataLabel) | Gibt einen Index des angegebenen DataLabel in der Sammlung zurück. |

### Siehe auch

* interface [IChartComponent](../ichartcomponent)
* interface [IDataLabel](../idatalabel)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->