---
title: set_Overlap()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि 2-डी चार्ट में बार और कॉलम कितनी प्रतिशत ओवरलैप करेंगे (-100% से 100% तक)।
type: docs
weight: 170
url: /hi/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) विधि


निर्दिष्ट करता है कि 2-डी चार्ट में बार और कॉलम कितनी प्रतिशत ओवरलैप करेंगे ( -100% से 100% तक)।

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## टिप्पणी


* -100%: अधिकतम अंतराल (बार पूरी तरह से अलग हो जाते हैं)।
* 0%: बार बिना ओवरलैप या अंतराल के एक के बगल में रखे जाते हैं।
* 100%: अधिकतम ओवरलैप (बार पूरी तरह से एक दूसरे के ऊपर होते हैं)। यह प्रॉपर्टी पढ़ने/लिखने योग्य **int8_t**।



निम्नलिखित उदाहरण दिखाता है कि चार्ट सीरीज़ ग्रुप के लिए ओवरलैप कैसे सेट करें और परिणामस्वरूप चार्ट को फॉर्म पर रेंडर करें: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // ओवरलैप को 55% पर सेट करें

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## अतिरिक्त देखें

* वर्ग [ChartSeriesGroup](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* पुस्तकालय [Aspose.Slides](../../../)