---
title: ChartSeriesGroup class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup क्लास

Represents group of series.

The ChartSeriesGroup type exposes the following members:

## गुण

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/type/) | इस श्रृंखला समूह का प्रकार लौटाता है।<br/>            Read-only [`CombinableSeriesTypesGroup`](/slides/python-net/hi/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | यदि इस समूह की श्रृंखला द्वितीयक अक्ष पर प्लॉट की गई है तो दर्शाता है।<br/>            Read-only **bool**. |
| [`series`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/series/) | श्रृंखलाओं का संग्रह लौटाता है।<br/>            Read-only [`IChartSeriesReadonlyCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Line- या Stock-चार्ट के up/down बार तक पहुंच प्रदान करता है।<br/>            Read-only [`IUpDownBarsManager`](/slides/python-net/hi/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/gap_width/) | बार या कॉलम समूहों के बीच की दूरी को, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है।<br/>            Read/write **int**. |
| [`gap_depth`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/gap_depth/) | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी को, मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है।<br/>            Read/write **int**. |
| [`first_slice_angle`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | पहले पाई या डोनट चार्ट स्लाइस का कोण प्राप्त करता या सेट करता है, <br/>            डिग्री में (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)।<br/>            Read/write **int**. |
| [`doughnut_hole_size`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत तक हो सकता है)।<br/>            Read/write **int**. |
| [`overlap`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/overlap/) | 2-D चार्ट में बार और कॉलम कितने ओवरलैप करेंगे, प्रतिशत में ( -100% से 100% तक)।<br/>             - -100%: अधिकतम अंतर (बार पूरी तरह अलग हैं)।<br/>             - 0%: बार साथ-साथ रखे जाते हैं बिना ओवरलैप या अंतर के।<br/>             - 100%: अधिकतम ओवरलैप (बार एक-दूसरे को पूरी तरह ओवरलैप करते हैं)।<br/>             This property is read/write **int**. |
| [`second_pie_size`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/second_pie_size/) | pie-of-pie चार्ट या bar-of-pie चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5 से 200 प्रतिशत के बीच हो सकता है)।<br/>            Read/write **int**. |
| [`bubble_size_representation`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | बबल चार्ट में बबल आकार मानों को कैसे दर्शाया जाता है, इसे निर्दिष्ट करता है।<br/>            Read/write [`BubbleSizeRepresentationType`](/slides/python-net/hi/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/pie_split_position/) | एक मान निर्दिष्ट करता है जिसे pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हैं, निर्धारित करने के लिए उपयोग किया जाएगा। यह PieSplitBy प्रॉपर्टी के साथ प्रयोग किया जाता है।<br/>            Read/write **float**. |
| [`pie_split_by`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/pie_split_by/) | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है।<br/>            Read/write [`PieSplitType`](/slides/python-net/hi/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/is_color_varied/) | श्रृंखला में प्रत्येक डेटा मार्कर का अलग रंग है, इसे निर्दिष्ट करता है।<br/>            Read/write **bool**. |
| [`has_series_lines`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/has_series_lines/) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्स्ड बार और OfPie चार्ट पर लागू।<br/>            Read/write **bool**. |
| [`hi_low_lines_format`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | HiLowLines प्रारूप निर्दिष्ट करता है।<br/>            HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है। |
| [`bubble_size_scale`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)।<br/>            Read/write **int**. |
| [`pie_split_custom_points`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | कस्टम स्प्लिट वाले pie-of-pie या bar-of-pie चार्ट के लिए कस्टम विभाजन जानकारी।<br/>            उन डेटा पॉइंट्स को शामिल करता है जिन्हें दूसरे पाई या बार में चित्रित किया जाना चाहिए।<br/>            Read-only [`PieSplitCustomPointCollection`](/slides/python-net/hi/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/chart/) | पेरेंट चार्ट लौटाता है।<br/>            Read-only [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/presentation/) |  |

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

## इंडेक्सर

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### टिप्पणियाँ

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup एनीम के लिए सारांश और टिप्पणी देखें.            
2) श्रृंखला का समूह कुछ श्रृंखला प्रॉपर्टीज़ रखता है जो समूह में प्रत्येक श्रृंखला के लिए सामान्य हैं ("series group properties").            
"Series group properties" ChartSeriesGroup क्लास में read/write है.            
"series group properties" में से प्रत्येक का ChartSeries क्लास में read-only प्रोजेक्शन हो सकता है.

### संबंधित देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)