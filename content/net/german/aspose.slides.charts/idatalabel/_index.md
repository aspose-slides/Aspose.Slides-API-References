---
title: IDataLabel
second_title: Aspose.Slides für .NET API Referenz
description: Stellt eine Serie von Beschriftungen dar.
type: docs
weight: 1940
url: /de/aspose.slides.charts/idatalabel/
---

## IDataLabel-Schnittstelle

Stellt eine Serie von Beschriftungen dar.

```csharp
public interface IDataLabel : IActualLayout, ILayoutable, IOverridableText
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/idatalabel/asiactuallayout) { get; } | Gibt die IActualLayout-Schnittstelle zurück. |
| [AsILayoutable](../../aspose.slides.charts/idatalabel/asilayoutable) { get; } | Gibt die ILayoutable-Schnittstelle zurück. Nur lesbar [`ILayoutable`](../ilayoutable). |
| [AsIOverridableText](../../aspose.slides.charts/idatalabel/asioverridabletext) { get; } | Gibt die IOverridableText-Schnittstelle zurück. Nur lesbar [`IOverridableText`](../ioverridabletext). |
| [DataLabelFormat](../../aspose.slides.charts/idatalabel/datalabelformat) { get; } | Gibt das Format der Datenbeschriftung zurück. Nur lesbar [`IDataLabelFormat`](../idatalabelformat). |
| [IsVisible](../../aspose.slides.charts/idatalabel/isvisible) { get; } | False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und alle Show*-Flags (ShowValue, ...) false sind). Nur lesbar Boolean. |
| [ValueFromCell](../../aspose.slides.charts/idatalabel/valuefromcell) { get; set; } | Holt oder setzt die Datenzelle des Arbeitsbuchs. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell gleich true ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetActualLabelText](../../aspose.slides.charts/idatalabel/getactuallabeltext)() | Gibt den aktuellen Beschriftungstext basierend auf den Einstellungen von DataLabelFormat oder dem Wert von TextFrameForOverriding.Text zurück. |
| [Hide](../../aspose.slides.charts/idatalabel/hide)() | Macht die Datenbeschriftung unsichtbar, indem alle Show*-Flags (ShowValue, ...) auf den Status false gesetzt werden. IsVisible wird danach false sein. |

### Siehe Auch

* Schnittstelle [IActualLayout](../iactuallayout)
* Schnittstelle [ILayoutable](../ilayoutable)
* Schnittstelle [IOverridableText](../ioverridabletext)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->