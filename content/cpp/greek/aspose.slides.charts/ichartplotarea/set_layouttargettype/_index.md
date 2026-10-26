---
title: set_LayoutTargetType()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η διάταξη της περιοχής σχεδίασης γίνεται εσωτερικά (χωρίς τους άξονες και τις ετικέτες των αξόνων) ή εξωτερικά (συμπεριλαμβανομένων των άξονων και των ετικετών των αξόνων). Γράψτε LayoutTargetType.
type: docs
weight: 27
url: /el/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) μέθοδος


Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η διάταξη της περιοχής σχεδίασης γίνεται εσωτερικά (χωρίς τους άξονες και τις ετικέτες των αξόνων) ή εξωτερικά (συμπεριλαμβανομένων των άξονων και των ετικετών των αξόνων). Γράψτε [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
```

## Παρατηρήσεις



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