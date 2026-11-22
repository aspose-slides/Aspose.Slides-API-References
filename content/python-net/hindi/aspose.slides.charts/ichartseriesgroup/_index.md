---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup वर्ग

श्रृंखलाओं के समूह को दर्शाता है।

IChartSeriesGroup प्रकार निम्न सदस्य प्रदर्शित करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`type`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/type/) | इस श्रृंखला समूह का प्रकार लौटाता है।<br/>            केवल-पढ़ने योग्य [`CombinableSeriesTypesGroup`](/slides/python-net/hi/aspose.slides.charts/combinableseriestypesgroup)। |
| [`plot_on_second_axis`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | यदि इस समूह की श्रृंखला द्वितीयक अक्ष पर चित्रित होती है तो दर्शाता है।<br/>            केवल-पढ़ने योग्य **bool**। |
| [`series`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/series/) | चार्ट श्रृंखलाओं का केवल-पढ़ने योग्य संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IChartSeriesReadonlyCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesreadonlycollection)। |
| [`up_down_bars`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Line- या Stock-चार्ट की ऊपर/नीचे बार तक पहुंच प्रदान करता है।<br/>            केवल-पढ़ने योग्य [`IUpDownBarsManager`](/slides/python-net/hi/aspose.slides.charts/iupdownbarsmanager)। |
| [`gap_width`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/gap_width/) | बार या कॉलम समूहों के बीच स्थान प्राप्त करता है या सेट करता है, जो बार या कॉलम की चौड़ाई का प्रतिशत है।<br/>            मान 0 से 500 के बीच होना चाहिए।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`gap_depth`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/gap_depth/) | 3D चार्ट में डेटा श्रृंखलाओं के बीच दूरी प्राप्त करता है या सेट करता है, जो मार्कर की चौड़ाई का प्रतिशत है।<br/>            मान 0 से 500 के बीच होना चाहिए।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`first_slice_angle`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | पहले पाई या डोनट चार्ट स्लाइस का कोण प्राप्त करता है या सेट करता है, <br/>            डिग्री में (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`is_color_varied`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`has_series_lines`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट में लागू।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`overlap`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/overlap/) | 2-डि चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में ( -100% से 100% तक)।<br/>             - -100%: अधिकतम अंतराल (बार पूरी तरह अलग हैं)।<br/>             - 0%: बार बगल-बगल रखे जाते हैं बिना ओवरलैप या अंतराल के।<br/>             - 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे के ऊपर होते हैं)।<br/>             यह गुण पढ़ने/लिखने योग्य **int** है। |
| [`second_pie_size`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | पाई-ऑफ़-पाई चार्ट या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5 से 200 प्रतिशत के बीच हो सकता है)।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`pie_split_position`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट हैं, यह निर्धारित करने के लिए उपयोग किया जाने वाला मान निर्दिष्ट करता है।<br/>            PieSplitBy गुण के साथ प्रयोग किया जाता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`pie_split_by`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट हैं, यह निर्धारित करने का तरीका निर्दिष्ट करता है।<br/>            पढ़ने/लिखने योग्य [`PieSplitType`](/slides/python-net/hi/aspose.slides.charts/piesplittype)। |
| [`pie_split_custom_points`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | कस्टम स्प्लिट वाले पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी।<br/>            उन डेटा पॉइंट्स को शामिल करता है जिन्हें दूसरे पाई या बार में चित्रित किया जाएगा।<br/>            केवल-पढ़ने योग्य [`IPieSplitCustomPointCollection`](/slides/python-net/hi/aspose.slides.charts/ipiesplitcustompointcollection)। |
| [`doughnut_hole_size`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार का 10 से 90 प्रतिशत के बीच)।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`bubble_size_scale`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार का 0 से 300 प्रतिशत के बीच)।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`hi_low_lines_format`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | HiLowLines फ़ॉर्मेट निर्दिष्ट करता है। <br/>            HiLowLines HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू होते हैं। |
| [`bubble_size_representation`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | बबल चार्ट में बबल आकार मान कैसे प्रदर्शित होते हैं, यह निर्दिष्ट करता है।<br/>            पढ़ने/लिखने योग्य [`BubbleSizeRepresentationType`](/slides/python-net/hi/aspose.slides.charts/bubblesizerepresentationtype)। |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

## सूचक

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### टिप्पणी

1) ChartSeriesGroupCollection वर्ग और CombinableSeriesTypesGroup enum के सारांश और टिप्पणी देखें।  
2) श्रृंखलाओं का समूह कुछ श्रृंखला गुण रखता है जो समूह में प्रत्येक श्रृंखला के लिए सामान्य हैं ("series group properties")। "Series group properties" ChartSeriesGroup वर्ग में पढ़ने/लिखने योग्य है। प्रत्येक "series group properties" का ChartSeries वर्ग में केवल-पढ़ने योग्य प्रोजेक्शन हो सकता है।

### देखें
* मॉड्युल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)