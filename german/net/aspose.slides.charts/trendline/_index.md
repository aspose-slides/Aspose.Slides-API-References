---
title: Trendline
second_title: Aspose.Slides für .NET-API-Referenz
description: Klasse repräsentiert Trendlinie der Diagrammserie
type: docs
weight: 2350
url: /de/net/aspose.slides.charts/trendline/
---
## Trendline class

-Klasse repräsentiert Trendlinie der Diagrammserie

```csharp
public class Trendline : DomObject<TrendlineCollection>, ITrendline
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Backward](../../aspose.slides.charts/trendline/backward) { get; set; } | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die sich die Trendlinie vor den Daten für die Trendreihe erstreckt. In Streudiagrammen und Nicht-Streudiagrammen muss der Wert ein beliebiger nichtnegativer Wert sein. Lesen/SchreibenDouble . |
| [Chart](../../aspose.slides.charts/trendline/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Schreibgeschützt[`IChart`](../ichart) . |
| [DisplayEquation](../../aspose.slides.charts/trendline/displayequation) { get; set; } | Gibt an, dass die Gleichung für die Trendlinie im Diagramm angezeigt wird (in der gleichen Bezeichnung wie der RQuadrat-Wert). Lesen/SchreibenBoolean . |
| [DisplayRSquaredValue](../../aspose.slides.charts/trendline/displayrsquaredvalue) { get; set; } | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (in derselben Bezeichnung wie die Gleichung). Lesen/SchreibenBoolean . |
| [Format](../../aspose.slides.charts/trendline/format) { get; set; } | Repräsentiert das Format der Trendlinie. Lesen/Schreiben[`IFormat`](../iformat) . |
| [Forward](../../aspose.slides.charts/trendline/forward) { get; set; } | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die sich die Trendlinie nach den -Daten für die Trendreihe erstreckt. In Streudiagrammen und Nicht-Streudiagrammen muss der Wert ein beliebiger nicht negativer Wert sein. Lesen/SchreibenDouble . |
| [Intercept](../../aspose.slides.charts/trendline/intercept) { get; set; } | Gibt den Wert an, bei dem die Trendlinie die y-Achse kreuzen soll. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lesen/SchreibenDouble . |
| [Order](../../aspose.slides.charts/trendline/order) { get; set; } | Gibt die Ordnung der Polynom-Trendlinie an. Bei anderen Trendlinientypen wird sie ignoriert. Wert muss zwischen 2 und 6 liegen. Lesen/SchreibenByte . |
| [Period](../../aspose.slides.charts/trendline/period) { get; set; } | Gibt den Zeitraum der Trendlinie für eine Trendlinie mit gleitendem Durchschnitt an. Sie wird für andere trend -Linienvarianten ignoriert. Wert muss zwischen 2 und 255 liegen. Lesen/SchreibenByte . |
| [RelatedLegendEntry](../../aspose.slides.charts/trendline/relatedlegendentry) { get; } | Stellt einen Legendeneintrag dar, der sich auf diese Trendlinie bezieht Schreibgeschützt[`ILegendEntryProperties`](../ilegendentryproperties) . |
| [TextFormat](../../aspose.slides.charts/trendline/textformat) { get; } | Gibt das Textformat zurück. Schreibgeschützt[`IChartTextFormat`](../icharttextformat) . |
| [TextFrameForOverriding](../../aspose.slides.charts/trendline/textframeforoverriding) { get; } | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert den automatisch generierten Text der Datenbeschriftung. Automatisch generierter Text der Datenbeschriftung bedeutet Text, der von den Eigenschaften ShowSeriesName, ShowValue, ... verwaltet und mit dem TextFormatManager formatiert wird .TextFormat-Eigenschaft. Schreibgeschützt[`ITextFrame`](../../aspose.slides/itextframe) . |
| [TrendlineName](../../aspose.slides.charts/trendline/trendlinename) { get; set; } | Ruft den Namen der Trendlinie ab oder legt ihn fest. Lesen/SchreibenString . |
| [TrendlineType](../../aspose.slides.charts/trendline/trendlinetype) { get; set; } | Holt oder setzt den Trendlinientyp. Lesen/Schreiben[`TrendlineType`](../trendlinetype) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/trendline/addtextframeforoverriding)(string) | Initialisiere TextFrameForOverriding mit dem Text im Parameter "text". Wenn TextFrameForOverriding bereits initialisiert ist, dann ändere einfach seinen Text. |

### Siehe auch

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [TrendlineCollection](../trendlinecollection)
* interface [ITrendline](../itrendline)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->