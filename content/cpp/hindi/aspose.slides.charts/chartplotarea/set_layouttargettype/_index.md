---
title: set_LayoutTargetType()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: यदि प्लॉट क्षेत्र की लेआउट मैन्युअल रूप से निर्धारित की जाती है, तो यह गुण यह निर्दिष्ट करता है कि प्लॉट क्षेत्र को उसके अंदर (अक्ष और अक्ष लेबल सहित नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। Write LayoutTargetType.
type: docs
weight: 183
url: /hi/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) विधि

यदि प्लॉट क्षेत्र की लेआउट मैन्युअल रूप से परिभाषित है, तो यह गुण यह बताता है कि प्लॉट क्षेत्र को उसके अंदर (अक्ष और अक्ष लेबल शामिल नहीं) या बाहर (अक्ष और अक्ष लेबल सहित) लेआउट किया जाए। लिखें [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
```

## टिप्पणी



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

## देखें

* Enum [LayoutTargetType](../../layouttargettype/)
* Class [ChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)