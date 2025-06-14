---
title: MasterTheme
second_title: Aspose.Sildes для .NET API Reference
description: Возвращает главную тему. Только для чтения IMasterThemeaspose.slides.theme/imastertheme.
type: docs
weight: 190
url: /ru/aspose.slides/presentation/mastertheme/
---

## Presentation.MasterTheme property

Возвращает главную тему. Только для чтения [`IMasterTheme`](../../../aspose.slides.theme/imastertheme).

```csharp
public IMasterTheme MasterTheme { get; }
```

### Примеры

В следующих примерах показано, как изменить эффект темы, изменив части элементов презентации PowerPoint.

```csharp
[C#]
//Instantiate a presentation object that represents a presentation file
using (Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx"))
{
    pres.MasterTheme.FormatScheme.LineStyles[0].FillFormat.SolidFillColor.Color = Color.Red;
    pres.MasterTheme.FormatScheme.FillStyles[2].FillType = FillType.Solid;
    pres.MasterTheme.FormatScheme.FillStyles[2].SolidFillColor.Color = Color.ForestGreen;
    pres.MasterTheme.FormatScheme.EffectStyles[2].EffectFormat.OuterShadowEffect.Distance = 10f;
    pres.Save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
}
```

### Смотрите Также

* interface [IMasterTheme](../../../aspose.slides.theme/imastertheme)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->