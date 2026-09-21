---
title: DataLabel class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/datalabel/
---
## DataLabel क्लास

एक श्रृंखला के लेबल का प्रतिनिधित्व करता है।

DataLabel प्रकार निम्न सदस्य प्रकट करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/hi/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | DataLabel क्लास की नई इंस्टेंस बनाता है। |

## प्रॉपर्टी

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/datalabel/chart/) | पैरेंट चार्ट लौटाता है।<br/>            केवल-पढ़ने योग्य [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/hi/aspose.slides.charts/datalabel/is_visible/) | False का मतलब है कि डेटा लेबल दृश्यमान नहीं है (और इसलिए सभी Show*-flags (ShowValue, ...) गलत हैं)।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/hi/aspose.slides.charts/datalabel/text_frame_for_overriding/) | एक समृद्ध फॉर्मेटेड टेक्स्ट रख सकता है। यदि यह प्रॉपर्टी None नहीं है तो यह <br/>            फॉर्मेटेड टेक्स्ट वैल्यू डेटा लेबल के स्वतः-जनरेटेड टेक्स्ट को ओवरराइड करती है।<br/>            डेटा लेबल का स्वतः-जनरेटेड टेक्स्ट वह टेक्स्ट है जिसे ShowSeriesName, <br/>            ShowValue, ... प्रॉपर्टीज़ द्वारा प्रबंधित किया जाता है और TextFormatManager.TextFormat प्रॉपर्टी के साथ फॉर्मेट किया जाता है।<br/>            केवल-पढ़ने योग्य [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/hi/aspose.slides.charts/datalabel/text_format/) | टेक्स्ट फॉर्मेट लौटाता है।<br/>            केवल-पढ़ने योग्य [`IChartTextFormat`](/slides/python-net/hi/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/hi/aspose.slides.charts/datalabel/x/) | शीर्षक का x निर्देशांक चार्ट की चौड़ाई के अनुपात में लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides.charts/datalabel/y/) | शीर्षक का y निर्देशांक चार्ट की ऊँचाई के अनुपात में लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides.charts/datalabel/width/) | शीर्षक की चौड़ाई चार्ट की चौड़ाई के अनुपात में लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides.charts/datalabel/height/) | शीर्षक की ऊँचाई चार्ट की ऊँचाई के अनुपात में लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`right`](/slides/python-net/hi/aspose.slides.charts/datalabel/right/) | दायाँ।<br/>            केवल-पढ़ने योग्य **float**. |
| [`bottom`](/slides/python-net/hi/aspose.slides.charts/datalabel/bottom/) | नीचा।<br/>            केवल-पढ़ने योग्य **float**. |
| [`data_label_format`](/slides/python-net/hi/aspose.slides.charts/datalabel/data_label_format/) | डेटा लेबल फ़ॉर्मेट लौटाता है।<br/>            केवल-पढ़ने योग्य [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/hi/aspose.slides.charts/datalabel/value_from_cell/) | वर्कबुक डेटा सेल को प्राप्त करता है या सेट करता है। लागू यदि IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true है। |
| [`actual_x`](/slides/python-net/hi/aspose.slides.charts/datalabel/actual_x/) | चार्ट एलिमेंट का वास्तविक x स्थान (बायाँ) चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है।<br/>            वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() मेथड को कॉल करें। <br/>            पढ़ें **float**. |
| [`actual_y`](/slides/python-net/hi/aspose.slides.charts/datalabel/actual_y/) | चार्ट एलिमेंट का वास्तविक शीर्ष चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है।<br/>            वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() मेथड को कॉल करें। <br/>            पढ़ें **float**. |
| [`actual_width`](/slides/python-net/hi/aspose.slides.charts/datalabel/actual_width/) | चार्ट एलिमेंट की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() मेथड को कॉल करें। <br/>            पढ़ें **float**. |
| [`actual_height`](/slides/python-net/hi/aspose.slides.charts/datalabel/actual_height/) | चार्ट एलिमेंट की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() मेथड को कॉल करें। <br/>            पढ़ें **float**. |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/datalabel/presentation/) |  |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`hide(self)`](/slides/python-net/hi/aspose.slides.charts/datalabel/hide/#) | सभी Show*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपा दें।<br/>            इस के बाद IsVisible false होगा। |
| [`get_actual_label_text(self)`](/slides/python-net/hi/aspose.slides.charts/datalabel/get_actual_label_text/#) | DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text वैल्यू के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है। |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/hi/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | पैरामीटर "text" में टेक्स्ट के साथ TextFrameForOverriding को इनिशियलाइज़ करें।<br/>            यदि TextFrameForOverriding पहले से इनिशियलाइज़ है तो केवल उसका टेक्स्ट बदलता है। |

### देखें भी
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)