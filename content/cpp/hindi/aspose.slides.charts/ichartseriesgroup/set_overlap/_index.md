---
title: set_Overlap()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि 2-D चार्ट्स पर बार और कॉलम कितनी प्रतिशत ( -100% से 100% तक) ओवरलैप करेंगे।
type: docs
weight: 196
url: /hi/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) विधि

निर्दिष्ट करता है कि 2-D चार्ट्स पर बार और कॉलम कितनी प्रतिशत ( -100% से 100% तक) ओवरलैप करेंगे।

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## टिप्पणी

* -100%: अधिकतम अंतर (बार पूरी तरह से अलग हैं)।
* 0%: बार बिना ओवरलैप या स्पेसिंग के साथ-साथ रखे जाते हैं।
* 100%: अधिकतम ओवरलैप (बार एक-दूसरे के ऊपर पूरी तरह से ओवरलैप होते हैं)। यह प्रॉपर्टी पढ़ने/लिखने योग्य **int8_t** है।

निम्न उदाहरण दर्शाता है कि चार्ट सीरीज़ समूह के लिए ओवरलैप कैसे सेट करें और फ़ॉर्म पर परिणामी चार्ट को रेंडर करें:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // ओवरलैप को 55% पर सेट करें

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## देखें

* क्लास [IChartSeriesGroup](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)