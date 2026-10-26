---
title: get_LayoutTargetType()
second_title: Aspose.Slides για την Αναφορά API C++
description: Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η διάταξη της περιοχής σχεδίασης θα γίνει από το εσωτερικό της (χωρίς τους άξονες και τις ετικέτες άξονα) ή από το εξωτερικό (με τους άξονες και τις ετικέτες άξονα). Διαβάστε LayoutTargetType.
type: docs
weight: 14
url: /el/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() μέθοδος

Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η διάταξη της περιοχής σχεδίασης θα γίνει από το εσωτερικό της (χωρίς τους άξονες και τις ετικέτες άξονα) ή από το εξωτερικό (με τους άξονες και τις ετικέτες άξονα). Διαβάστε [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## Σχόλια

```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 20.0f, 100.0f, 600.0f, 400.0f);

chart->get_PlotArea()->set_X(0.2f);
chart->get_PlotArea()->set_Y(0.2f);
chart->get_PlotArea()->set_Width(0.7f);
chart->get_PlotArea()->set_Height(0.7f);

chart->get_PlotArea()->set_LayoutTargetType(LayoutTargetType::Inner);
// ...
```

## Δείτε επίσης

* Απαρίθμηση [LayoutTargetType](../../layouttargettype/)
* Κλάση [IChartPlotArea](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)