---
title: get_Overlap()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट करता है कि 2-D चार्टों पर बार और कॉलम कितने प्रतिशत ( -100% से 100% तक) ओवरलैप करेंगे।
type: docs
weight: 157
url: /hi/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() मेथड

निर्दिष्ट करता है कि 2-D चार्ट पर बार और कॉलम कितने प्रतिशत ( -100% से 100% तक) ओवरलैप करेंगे।

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## टिप्पणी

* -100%: अधिकतम स्पेसिंग (बार पूरी तरह से अलग हैं)।
* 0%: बार बगल बगल रखे जाते हैं बिना ओवरलैप या स्पेसिंग के।
* 100%: अधिकतम ओवरलैप (बार एक-दूसरे के ऊपर पूरी तरह से ओवरलैप होते हैं)। यह प्रॉपर्टी पढ़ने/लिखने योग्य **int8_t** है।

निम्नलिखित उदाहरण दिखाता है कि कैसे चार्ट सीरीज़ समूह के लिए ओवरलैप सेट करें और फ़ॉर्म पर परिणामी चार्ट रेंडर करें: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // ओवरलैप को 55% सेट करें

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## देखें

* क्लास [ChartSeriesGroup](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)