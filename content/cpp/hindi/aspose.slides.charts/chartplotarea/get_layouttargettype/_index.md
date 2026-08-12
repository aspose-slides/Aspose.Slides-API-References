---
title: get_LayoutTargetType()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि प्लॉट एरिया का लेआउट मैन्युअल रूप से परिभाषित किया गया है, तो यह प्रॉपर्टी यह निर्दिष्ट करती है कि प्लॉट एरिया को उसके अंदर (एक्सिस और एक्सिस लेबल को बाहर रखे बिना) लेआउट किया जाए या बाहर (एक्सिस और एक्सिस लेबल सहित)। पढ़ें LayoutTargetType.
type: docs
weight: 170
url: /hi/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() मेथड


यदि प्लॉट एरिया का लेआउट मैन्युअल रूप से परिभाषित किया गया है, तो यह प्रॉपर्टी यह निर्दिष्ट करती है कि प्लॉट एरिया को उसके अंदर (एक्सिस और एक्सिस लेबल को बाहर रखते हुए) लेआउट किया जाए या बाहर (एक्सिस और एक्सिस लेबल को शामिल करते हुए)। पढ़ें [LayoutTargetType](../../layouttargettype/)।

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
```

## टिप्पणियाँ



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
* क्लास [ChartPlotArea](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)