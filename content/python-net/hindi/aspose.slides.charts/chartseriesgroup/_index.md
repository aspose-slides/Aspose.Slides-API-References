---
title: ChartSeriesGroup class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup क्लास

श्रृंखला के समूह का प्रतिनिधित्व करता है।

ChartSeriesGroup प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`type`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/type/) | इस श्रृंखला समूह का प्रकार लौटाता है.<br/>            केवल पढ़ने योग्य [`CombinableSeriesTypesGroup`](/slides/python-net/hi/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | संकते करता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर दर्शाई गई हैं या नहीं.<br/>            केवल पढ़ने योग्य **bool**. |
| [`series`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/series/) | श्रृंखलाओं का संग्रह लौटाता है.<br/>            केवल पढ़ने योग्य [`IChartSeriesReadonlyCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Line- या Stock-चार्ट की ऊपर/नीचे बार तक पहुंच प्रदान करता है.<br/>            केवल पढ़ने योग्य [`IUpDownBarsManager`](/slides/python-net/hi/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/gap_width/) | बार या कॉलम क्लस्टर के बीच की जगह प्राप्त करता है या सेट करता है, जो बार या कॉलम की चौड़ाई के प्रतिशत में है.<br/>            मान 0 और 500 के बीच होना चाहिए.<br/>            पढ़ने/लिखने योग्य **int**. |
| [`gap_depth`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/gap_depth/) | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी प्राप्त करता है या सेट करता है, जो मार्कर की चौड़ाई के प्रतिशत में है.<br/>            मान 0 और 500 के बीच होना चाहिए.<br/>            पढ़ने/लिखने योग्य **int**. |
| [`first_slice_angle`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | पहले पाई या डोनट चार्ट स्लाइस के कोण को प्राप्त करता है या सेट करता है, <br/>            डिग्री में (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक).<br/>            पढ़ने/लिखने योग्य **int**. |
| [`doughnut_hole_size`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | डोनट चार्ट में छेद के आकार को निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत के बीच हो सकता है).<br/>            पढ़ने/लिखने योग्य **int**. |
| [`overlap`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/overlap/) | 2-D चार्ट पर बार और कॉलम कितने प्रतिशत ओवरलैप करेंगे, यह प्रतिशत के रूप में निर्दिष्ट करता है ( -100% से 100% तक).<br/>             - -100%: अधिकतम अंतर (बार पूरी तरह से अलग हैं).<br/>             - 0%: बार बिना ओवरलैप या अंतर के साथ बगल में रखे जाते हैं.<br/>             - 100%: अधिकतम ओवरलैप (बार एक-दूसरे पर पूरी तरह से ओवरलैप होते हैं).<br/>             यह गुण पढ़ने/लिखने योग्य **int**. |
| [`second_pie_size`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/second_pie_size/) | pie-of-pie चार्ट या <br/>            bar-of-pie चार्ट में दूसरे पाई या बार के आकार को निर्दिष्ट करता है, जो पहले पाई के आकार के प्रतिशत में है (5 से 200 प्रतिशत के बीच हो सकता है).<br/>            पढ़ने/लिखने योग्य **int**. |
| [`bubble_size_representation`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | बबल चार्ट पर बबल आकार मानों को कैसे प्रस्तुत किया जाता है, यह निर्दिष्ट करता है.<br/>            पढ़ने/लिखने योग्य [`BubbleSizeRepresentationType`](/slides/python-net/hi/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/pie_split_position/) | एक मान निर्दिष्ट करता है जो निर्धारित करने के लिए उपयोग होगा कि कौन से डेटा पॉइंट <br/>            दूसरे पाई या बार में हैं pie-of-pie या bar-of-pie चार्ट में. <br/>            PieSplitBy गुण के साथ उपयोग किया जाता है.<br/>            पढ़ने/लिखने योग्य **float**. |
| [`pie_split_by`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/pie_split_by/) | निश्चित करता है कि कैसे निर्धारित किया जाए कि कौन से डेटा पॉइंट दूसरे पाई या बार में हैं <br/>            pie-of-pie या bar-of-pie चार्ट में.<br/>            पढ़ने/लिखने योग्य [`PieSplitType`](/slides/python-net/hi/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/is_color_varied/) | निर्धारित करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का अलग रंग हो.<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`has_series_lines`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/has_series_lines/) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य. स्टैक्ड बार और OfPie चार्ट पर लागू.<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`hi_low_lines_format`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | HiLowLines फ़ॉर्मेट निर्दिष्ट करता है. <br/>            HiLowLines HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू होते हैं. |
| [`bubble_size_scale`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है).<br/>            पढ़ने/लिखने योग्य **int**. |
| [`pie_split_custom_points`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | एक कस्टम स्प्लिट वाले pie-of-pie या bar-of-pie चार्ट के लिए कस्टम स्प्लिट जानकारी.<br/>            डेटा पॉइंट शामिल करता है जो दूसरे पाई या बार में खींचे जाएंगे pie-of-pie या <br/>            bar-of-pie चार्ट में.<br/>            केवल पढ़ने योग्य [`PieSplitCustomPointCollection`](/slides/python-net/hi/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/chart/) | पैरेंट चार्ट लौटाता है.<br/>            केवल पढ़ने योग्य [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/presentation/) |  |

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

## Indexer

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### टिप्पणी

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup enum के लिए सारांश और टिप्पणी देखें.
            2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह में प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("series group properties").
            "Series group properties" ChartSeriesGroup क्लास में पढ़ने/लिखने योग्य है.
            प्रत्येक "series group properties" का एक केवल पढ़ने योग्य प्रोजेक्शन ChartSeries क्लास में हो सकता है.

### देखें भी
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)