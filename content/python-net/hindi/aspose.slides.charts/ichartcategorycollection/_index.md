---
title: IChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection क्लास

[`IChartCategory`](/slides/python-net/hi/aspose.slides.charts/ichartcategory) का संग्रह दर्शाता है

The IChartCategoryCollection type exposes the following members:

## गुण

| गुण | विवरण |
| :- | :- |
| [`use_cells`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection/use_cells/) | यदि true हो तो worksheet श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (इस केस में बहु-स्तरीय श्रेणियों का समर्थन होता है)।<br/>यदि false हो तो worksheet मान संग्रहीत करने के लिए उपयोग नहीं किया जाता (और इस केस में बहु-स्तरीय श्रेणियों का समर्थन नहीं होता)।<br/>पढ़ें/लिखें **bool**. |
| [`grouping_level_count`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | उपयोग किए गए श्रेणी समूह स्तरों की संख्या लौटाता है।<br/>बहु-स्तरीय श्रेणियों के लिए यह एक से अधिक होता है।<br/>केवल-पढ़ने योग्य **int**. |

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

## इंडेक्सर

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | यदि संग्रह में श्रेणी मौजूद है, तो उसे लौटाएं। अन्यथा <br/>[`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) से नया chart category बनाता है और उसे संग्रह में जोड़ता है। |
| [`add(self, value)`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection/add/#any) | मान से नया [`IChartCategory`](/slides/python-net/hi/aspose.slides.charts/ichartcategory) बनाता है और उसे संग्रह में जोड़ता है। |
| [`index_of(self, value)`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | निर्दिष्ट [`IChartCategory`](/slides/python-net/hi/aspose.slides.charts/ichartcategory) को खोजता है और पूरी Collection में पहली घटना का शून्य-आधारित सूचकांक लौटाता है |
| [`remove(self, value)`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | निर्दिष्ट मान को हटाता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | दिए गए सूचकांक पर तत्व को हटाता है। |
| [`clear(self)`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection/clear/#) | संग्रह से सभी तत्वों को हटाता है। |


### देखें भी
* क्लास [`IChartCategory`](/slides/python-net/hi/aspose.slides.charts/ichartcategory)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)