---
title: DataLabel class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.charts/datalabel/
---
## DataLabel वर्ग

एक श्रृंखला के लेबल को दर्शाता है।

DataLabel प्रकार निम्न सदस्य प्रदान करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/hi/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | DataLabel वर्ग की नई उदाहरण बनाता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/datalabel/chart/) | पैरेंट चार्ट को लौटाता है।<br/>            केवल पढ़ने योग्य [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/hi/aspose.slides.charts/datalabel/is_visible/) | False का अर्थ है कि डेटा लेबल दृश्यमान नहीं है (और इसलिए सभी Show*-flags (ShowValue, ...) false होते हैं)।<br/>            केवल पढ़ने योग्य **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/hi/aspose.slides.charts/datalabel/text_frame_for_overriding/) | समृद्ध स्वरूपित पाठ शामिल कर सकता है। यदि यह गुण None नहीं है तो यह <br/>            स्वरूपित पाठ मान डेटा लेबल के स्वतः-उत्पन्न पाठ को ओवरराइड करता है।<br/>            डेटा लेबल का स्वतः-उत्पन्न पाठ वह पाठ है जिसे ShowSeriesName, <br/>            ShowValue, ... गुणों द्वारा प्रबंधित किया जाता है और TextFormatManager.TextFormat गुण के साथ स्वरूपित किया जाता है।<br/>            केवल पढ़ने योग्य [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/hi/aspose.slides.charts/datalabel/text_format/) | पाठ स्वरूप लौटाता है।<br/>            केवल पढ़ने योग्य [`IChartTextFormat`](/slides/python-net/hi/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/hi/aspose.slides.charts/datalabel/x/) | शीर्षक के x निर्देशांक को चार्ट की चौड़ाई के अनुपात में लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides.charts/datalabel/y/) | शीर्षक के y निर्देशांक को चार्ट की ऊँचाई के अनुपात में लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides.charts/datalabel/width/) | शीर्षक की चौड़ाई को चार्ट की चौड़ाई के अनुपात में लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides.charts/datalabel/height/) | शीर्षक की ऊँचाई को चार्ट की ऊँचाई के अनुपात में लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`right`](/slides/python-net/hi/aspose.slides.charts/datalabel/right/) | दायाँ।<br/>            केवल पढ़ने योग्य **float**. |
| [`bottom`](/slides/python-net/hi/aspose.slides.charts/datalabel/bottom/) | नीचा।<br/>            केवल पढ़ने योग्य **float**. |
| [`data_label_format`](/slides/python-net/hi/aspose.slides.charts/datalabel/data_label_format/) | डेटा लेबल स्वरूप लौटाता है।<br/>            केवल पढ़ने योग्य [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/hi/aspose.slides.charts/datalabel/value_from_cell/) | वर्कबुक डेटा सेल को प्राप्त करता या सेट करता है। यदि IDataLabelFormat.ShowLabelValueFromCell गुण true है तो लागू होता है। |
| [`label_shape_type`](/slides/python-net/hi/aspose.slides.charts/datalabel/label_shape_type/) | डेटा लेबल के आकार प्रकार को प्राप्त करता या सेट करता है।<br/>             यदि कोई आकार परिभाषित नहीं है तो [`ShapeType.NOT_DEFINED`](/slides/python-net/hi/aspose.slides/shapetype/NOT_DEFINED) लौटाता है। |
| [`actual_x`](/slides/python-net/hi/aspose.slides.charts/datalabel/actual_x/) | चार्ट तत्व के वास्तविक x स्थान (बाएँ) को चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है।<br/>            वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। <br/>            पढ़ें **float**. |
| [`actual_y`](/slides/python-net/hi/aspose.slides.charts/datalabel/actual_y/) | चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है।<br/>            वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। <br/>            पढ़ें **float**. |
| [`actual_width`](/slides/python-net/hi/aspose.slides.charts/datalabel/actual_width/) | चार्ट तत्व की वास्तविक चौड़ाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। <br/>            पढ़ें **float**. |
| [`actual_height`](/slides/python-net/hi/aspose.slides.charts/datalabel/actual_height/) | चार्ट तत्व की वास्तविक ऊँचाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। <br/>            पढ़ें **float**. |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/datalabel/presentation/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`hide(self)`](/slides/python-net/hi/aspose.slides.charts/datalabel/hide/#) | सभी Show*-flags (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपा देता है।<br/>            इस के बाद IsVisible false होगा। |
| [`get_actual_label_text(self)`](/slides/python-net/hi/aspose.slides.charts/datalabel/get_actual_label_text/#) | DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल पाठ लौटाता है। |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/hi/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | TextFrameForOverriding को पैरामीटर "text" में दिए गए पाठ से प्रारंभ करता है।<br/>            यदि TextFrameForOverriding पहले से प्रारंभ किया गया है तो बस उसका पाठ बदल देता है। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)