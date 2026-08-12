---
title: get_LayoutTargetType()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि प्लॉट एरिया की लेआउट मैन्युअली परिभाषित की गई है, तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (अक्ष और अक्ष लेबल को शामिल नहीं करता) या बाहर (अक्ष और अक्ष लेबल को शामिल करता) लेआउट किया जाए। पढ़ें LayoutTargetType.
type: docs
weight: 14
url: /hi/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() मेथड


यदि प्लॉट एरिया की लेआउट मैन्युअल रूप से निर्धारित की गई है, तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (अक्ष और अक्ष लेबल को शामिल नहीं करता) या बाहर (अक्ष और अक्ष लेबल को शामिल करता) लेआउट किया जाए। पढ़ें [LayoutTargetType](../../layouttargettype/)।

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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

## संबंधित देखें

* एन्यूम [LayoutTargetType](../../layouttargettype/)
* क्लास [IChartPlotArea](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)