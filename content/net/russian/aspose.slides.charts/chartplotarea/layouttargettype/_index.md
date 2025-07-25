---
title: LayoutTargetType
second_title: Aspose.Sildes для .NET API Справочник
description: Если компоновка области графика определена вручную, это свойство указывает, нужно ли располагать область графика внутри не включая оси и подписи к осям или снаружи включая оси и подписи к осям. Чтение/запись LayoutTargetTypeaspose.slides.charts/chartplotarea/layouttargettype.
type: docs
weight: 100
url: /ru/aspose.slides.charts/chartplotarea/layouttargettype/
---

## ChartPlotArea.LayoutTargetType свойство

Если компоновка области графика определена вручную, это свойство указывает, нужно ли располагать область графика внутри (не включая оси и подписи к осям) или снаружи (включая оси и подписи к осям). Чтение/запись `LayoutTargetType`.

```csharp
public LayoutTargetType LayoutTargetType { get; set; }
```

### Примеры

```csharp
using (Presentation presentation = new Presentation())

    ISlide slide = presentation.Slides[0];
    IChart chart = slide.Shapes.AddChart(ChartType.ClusteredColumn, 20, 100, 600, 400);

    chart.PlotArea.AsILayoutable.X = 0.2f;
    chart.PlotArea.AsILayoutable.Y = 0.2f;
    chart.PlotArea.AsILayoutable.Width = 0.7f;
    chart.PlotArea.AsILayoutable.Height = 0.7f;

    chart.PlotArea.LayoutTargetType = LayoutTargetType.Inner;
    ...

```

### Смотрите также

* enum [LayoutTargetType](../../layouttargettype)
* class [ChartPlotArea](../../chartplotarea)
* namespace [Aspose.Slides.Charts](../../chartplotarea)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->