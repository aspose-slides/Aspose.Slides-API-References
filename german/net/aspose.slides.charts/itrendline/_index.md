---
title: ITrendline
second_title: Aspose.Slides für .NET-API-Referenz
description: Klasse repräsentiert Trendlinie der Diagrammserie
type: docs
weight: 2120
url: /de/net/aspose.slides.charts/itrendline/
---
## ITrendline interface

-Klasse repräsentiert Trendlinie der Diagrammserie

```csharp
public interface ITrendline : IOverridableText
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIOverridableText](../../aspose.slides.charts/itrendline/asioverridabletext) { get; } | Gibt die IOverridableText-Schnittstelle zurück. Schreibgeschützt[`IOverridableText`](../ioverridabletext) . |
| [Backward](../../aspose.slides.charts/itrendline/backward) { get; set; } | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die sich die Trendlinie vor den Daten für die Trendreihe erstreckt. In Streudiagrammen und Nicht-Streudiagrammen muss der Wert ein beliebiger nichtnegativer Wert sein. Lesen/SchreibenDouble . |
| [DisplayEquation](../../aspose.slides.charts/itrendline/displayequation) { get; set; } | Gibt an, dass die Gleichung für die Trendlinie im Diagramm angezeigt wird (in der gleichen Bezeichnung wie der RQuadrat-Wert). Lesen/SchreibenBoolean . |
| [DisplayRSquaredValue](../../aspose.slides.charts/itrendline/displayrsquaredvalue) { get; set; } | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (in derselben Bezeichnung wie die Gleichung). Lesen/SchreibenBoolean . |
| [Format](../../aspose.slides.charts/itrendline/format) { get; set; } | Repräsentiert das Format der Trendlinie. Lesen/Schreiben[`IFormat`](../iformat) . |
| [Forward](../../aspose.slides.charts/itrendline/forward) { get; set; } | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die sich die Trendlinie nach den -Daten für die Trendreihe erstreckt. In Streudiagrammen und Nicht-Streudiagrammen muss der Wert ein beliebiger nicht negativer Wert sein. Lesen/SchreibenDouble . |
| [Intercept](../../aspose.slides.charts/itrendline/intercept) { get; set; } | Gibt den Wert an, bei dem die Trendlinie die y-Achse kreuzen soll. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lesen/SchreibenDouble . |
| [Order](../../aspose.slides.charts/itrendline/order) { get; set; } | Gibt die Ordnung der Polynom-Trendlinie an. Bei anderen Trendlinientypen wird sie ignoriert. Wert muss zwischen 2 und 6 liegen. Lesen/SchreibenByte . |
| [Period](../../aspose.slides.charts/itrendline/period) { get; set; } | Gibt den Zeitraum der Trendlinie für eine Trendlinie mit gleitendem Durchschnitt an. Sie wird für andere trend -Linienvarianten ignoriert. Wert muss zwischen 2 und 255 liegen. Lesen/SchreibenByte . |
| [RelatedLegendEntry](../../aspose.slides.charts/itrendline/relatedlegendentry) { get; } | Stellt einen Legendeneintrag dar, der sich auf diese Trendlinie bezieht Schreibgeschützt[`ILegendEntryProperties`](../ilegendentryproperties) . |
| [TrendlineName](../../aspose.slides.charts/itrendline/trendlinename) { get; set; } | Ruft den Namen der Trendlinie ab oder legt ihn fest. Lesen/SchreibenString . |
| [TrendlineType](../../aspose.slides.charts/itrendline/trendlinetype) { get; set; } | Holt oder setzt den Trendlinientyp. Lesen/Schreiben[`TrendlineType`](./trendlinetype) . |

### Siehe auch

* interface [IOverridableText](../ioverridabletext)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->