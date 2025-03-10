---
title: IDataLabel
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert eine Serienbeschriftung.
type: docs
weight: 1900
url: /de/aspose.slides.charts/idatalabel/
---
## IDataLabel interface

Repräsentiert eine Serienbeschriftung.

```csharp
public interface IDataLabel : IActualLayout, ILayoutable, IOverridableText
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/idatalabel/asiactuallayout) { get; } | Gibt die IActualLayout-Schnittstelle zurück. |
| [AsILayoutable](../../aspose.slides.charts/idatalabel/asilayoutable) { get; } | Gibt ILayoutable-Schnittstelle zurück. Schreibgeschützt[`ILayoutable`](../ilayoutable) . |
| [AsIOverridableText](../../aspose.slides.charts/idatalabel/asioverridabletext) { get; } | Gibt die IOverridableText-Schnittstelle zurück. Schreibgeschützt[`IOverridableText`](../ioverridabletext) . |
| [DataLabelFormat](../../aspose.slides.charts/idatalabel/datalabelformat) { get; } | Gibt das Format des Datenlabels zurück. Schreibgeschützt[`IDataLabelFormat`](../idatalabelformat) . |
| [IsVisible](../../aspose.slides.charts/idatalabel/isvisible) { get; } | False bedeutet, dass das Datenlabel nicht sichtbar ist (und daher sind alle Show*-Flags (ShowValue, ...) falsch). Read-onlyBoolean . |
| [ValueFromCell](../../aspose.slides.charts/idatalabel/valuefromcell) { get; set; } | Ruft Arbeitsmappen-Datenzelle ab oder legt sie fest. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell gleich true ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetActualLabelText](../../aspose.slides.charts/idatalabel/getactuallabeltext)() | Gibt den tatsächlichen Beschriftungstext basierend auf den DataLabelFormat-Einstellungen oder dem TextFrameForOverriding.Text-Wert zurück. |
| [Hide](../../aspose.slides.charts/idatalabel/hide)() | Datenbeschriftung unsichtbar machen, indem alle Show*-Flags (ShowValue, ...) auf false gesetzt werden. IsVisible ist danach false. |

### Siehe auch

* interface [IActualLayout](../iactuallayout)
* interface [ILayoutable](../ilayoutable)
* interface [IOverridableText](../ioverridabletext)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
