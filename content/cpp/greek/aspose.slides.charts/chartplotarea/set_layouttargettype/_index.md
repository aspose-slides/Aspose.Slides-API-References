---
title: set_LayoutTargetType()
second_title: Αναφορά API Aspose.Slides για C++
description: Εάν η διάταξη της περιοχής γραφήματος ορίζεται χειροκίνητα αυτή η ιδιότητα καθορίζει αν η διάταξη της περιοχής γραφήματος γίνεται από το εσωτερικό της (χωρίς τους άξονες και τις ετικέτες άξονα) ή από το εξωτερικό της (με τους άξονες και τις ετικέτες άξονα). Γράψτε LayoutTargetType.
type: docs
weight: 183
url: /el/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) μέθοδος


Εάν η διάταξη της περιοχής γραφήματος ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει αν η διάταξη της περιοχής γραφήματος γίνεται από το εσωτερικό της (χωρίς τους άξονες και τις ετικέτες άξονα) ή από το εξωτερικό της (με τους άξονες και τις ετικέτες άξονα). Γράψτε [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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
* Τάξη [ChartPlotArea](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)