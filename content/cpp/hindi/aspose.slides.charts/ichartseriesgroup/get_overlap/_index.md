---
title: get_Overlap()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्देश देता है कि 2-डी चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत के रूप में ( -100% से 100% तक)।
type: docs
weight: 183
url: /hi/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() मेथड


निर्देश देता है कि 2-डी चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत के रूप में ( -100% से 100% तक)।

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## टिप्पणियाँ


* -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग होते हैं)।
* 0%: बार बगल बगल रखे जाते हैं बिना ओवरलैप या स्पेसिंग के।
* 100%: अधिकतम ओवरलैप (बार पूरी तरह एक दूसरे पर ओवरलैप करते हैं)। यह प्रॉपर्टी पढ़ने/लिखने योग्य **int8_t** है।



निम्नलिखित उदाहरण दर्शाता है कि चार्ट सीरीज़ ग्रुप के ओवरलैप को कैसे सेट करें और फॉर्म पर परिणामी चार्ट को रेंडर करें: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // ओवरलैप को 55% पर सेट करें

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## संबंधित देखें

* क्लास [IChartSeriesGroup](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)