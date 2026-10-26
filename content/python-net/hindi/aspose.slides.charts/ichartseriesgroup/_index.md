---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup क्लास

श्रृंखला समूह का प्रतिनिधित्व करता है।

IChartSeriesGroup प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`type`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/type/) | इस श्रृंखला समूह का प्रकार लौटाता है।<br/>            केवल पढ़ने योग्य [`CombinableSeriesTypesGroup`](/slides/python-net/hi/aspose.slides.charts/combinableseriestypesgroup)। |
| [`plot_on_second_axis`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | यह दर्शाता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`series`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/series/) | चार्ट श्रृंखला की केवल-पढ़ने योग्य संग्रह लौटाता है।<br/>            केवल पढ़ने योग्य [`IChartSeriesReadonlyCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesreadonlycollection)। |
| [`up_down_bars`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | लाइन- या स्टॉक-चार्ट की उप/नीचे बार तक पहुँच प्रदान करता है।<br/>            केवल पढ़ने योग्य [`IUpDownBarsManager`](/slides/python-net/hi/aspose.slides.charts/iupdownbarsmanager)। |
| [`gap_width`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/gap_width/) | बार या कॉलम क्लस्टर्स के बीच की जगह, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`gap_depth`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/gap_depth/) | 3D चार्ट में डेटा श्रृंखलाओं के बीच दूरी, मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`first_slice_angle`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | पहले पाई या डोनट चार्ट स्लाइस का कोण सेट या प्राप्त करता है, <br/>            डिग्री में (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`is_color_varied`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | यह निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग हो।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`has_series_lines`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सही। स्टैक्ड बार और OfPie चार्ट पर लागू होता है।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`overlap`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/overlap/) | 2-D चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में (-100% से 100% तक) निर्दिष्ट करता है।<br/>             - -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग हैं)।<br/>             - 0%: बार बिना ओवरलैप या स्पेसिंग के साइड-बाय-साइड रखे जाते हैं।<br/>             - 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप करते हैं)।<br/>             यह प्रॉपर्टी पढ़ने/लिखने योग्य **int** है। |
| [`second_pie_size`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 % से 200 % तक हो सकता है)।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`pie_split_position`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | वह मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाता है कि कौन-से डेटा पॉइंट दूसरे पाई या बार में हैं पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट पर।<br/>            PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`pie_split_by`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | यह निर्धारित करने का तरीका निर्दिष्ट करता है कि कौन-से डेटा पॉइंट दूसरे पाई या बार में हैं पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट पर।<br/>            पढ़ने/लिखने योग्य [`PieSplitType`](/slides/python-net/hi/aspose.slides.charts/piesplittype)। |
| [`pie_split_custom_points`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | कस्टम स्प्लिट के साथ पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम स्प्लिट जानकारी।<br/>            डेटा पॉइंट सम्मिलित करता है जो दूसरे पाई या बार में ड्रॉ किए जाने चाहिए पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में।<br/>            केवल पढ़ने योग्य [`IPieSplitCustomPointCollection`](/slides/python-net/hi/aspose.slides.charts/ipiesplitcustompointcollection)। |
| [`doughnut_hole_size`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10 % से 90 % तक)।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`bubble_size_scale`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | बुलबुले चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 % से 300 % तक)।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`hi_low_lines_format`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | HiLowLines का प्रारूप निर्दिष्ट करता है। <br/>            HiLowLines HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू होते हैं। |
| [`bubble_size_representation`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | बुलबुले आकार मानों को बुलबुले चार्ट पर कैसे प्रस्तुत किया जाता है, निर्दिष्ट करता है।<br/>            पढ़ने/लिखने योग्य [`BubbleSizeRepresentationType`](/slides/python-net/hi/aspose.slides.charts/bubblesizerepresentationtype)। |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

## इंडेक्सर

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### टिप्पणियाँ

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup एन्यूम के लिए सारांश और टिप्पणियाँ देखें।  
2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह के प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("श्रृंखला समूह गुण")।  
   ChartSeriesGroup क्लास में "श्रृंखला समूह गुण" पढ़ने/लिखने योग्य हैं।  
   प्रत्येक "श्रृंखला समूह गुण" का ChartSeries क्लास में केवल-पढ़ने योग्य प्रोजेक्शन हो सकता है।

### संबंधित देखें
* मोड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)