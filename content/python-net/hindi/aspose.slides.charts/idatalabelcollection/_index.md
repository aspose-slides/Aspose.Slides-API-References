---
title: IDataLabelCollection class
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection क्लास

एक श्रृंखला लेबल का प्रतिनिधित्व करता है।

IDataLabelCollection प्रकार निम्नलिखित सदस्य प्रदान करता है:

## गुण

| संपत्ति | विवरण |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | संग्रह में सभी डेटा लेबल का डिफ़ॉल्ट फ़ॉर्मेट वापस करता है।<br/> केवल-पढ़ने योग्य [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | डेटा लेबल के लीडर लाइनों के फ़ॉर्मेट का प्रतिनिधित्व करता है।<br/> केवल-पढ़ने योग्य [`IChartLinesFormat`](/slides/python-net/hi/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/is_visible/) | False का मतलब है कि डेटा लेबल डिफ़ॉल्ट रूप से दृश्यमान नहीं है (और इसलिए सभी <br/> Show*-flags (ShowValue, ...) DefaultDataLabelFormat प्रॉपर्टी के false होते हैं).<br/> केवल-पढ़ने योग्य **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | संग्रह में दृश्यमान डेटा लेबल की संख्या प्राप्त करता है।<br/> केवल-पढ़ने योग्य **int**. |
| [`count`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/count/) | संग्रह में सभी डेटा लेबल की संख्या प्राप्त करता है।<br/> केवल-पढ़ने योग्य **int**. |
| [`parent_series`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/parent_series/) | पैरेंट चार्ट सीरीज़ को वापस करता है।<br/> केवल-पढ़ने योग्य [`IChartSeries`](/slides/python-net/hi/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | डेटा लेबल के लिए डिफ़ॉल्ट शैप प्रकार प्राप्त करता है या सेट करता है।<br/> यदि कोई शैप निर्धारित नहीं है तो [`ShapeType.NOT_DEFINED`](/slides/python-net/hi/aspose.slides/shapetype/NOT_DEFINED) लौटाता है। |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/presentation/) |  |

निर्दिष्ट सूचकांक वाले डेटा पॉइंट के लिए डेटा लेबल प्राप्त करता है।

## इंडेक्सर

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`hide(self)`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/hide/#) | डेटा लेबल को डिफ़ॉल्ट रूप से छिपा हुआ बनाएं सभी Show*-flags (ShowValue, ...) को DefaultDataLabelFormat प्रॉपर्टी में false स्थिति में सेट करके।<br/> इस के बाद IsVisible false होगा। |
| [`index_of(self, value)`](/slides/python-net/hi/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | संग्रह में निर्दिष्ट DataLabel का सूचकांक लौटाता है। |


### संबंधित देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)