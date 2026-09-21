---
title: ChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection क्लास

प्रस्तुत करता है [`ChartCategory`](/slides/python-net/hi/aspose.slides.charts/chartcategory) का संग्रह

The ChartCategoryCollection type exposes the following members:

## गुण

| गुण | विवरण |
| :- | :- |
| [`use_cells`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection/use_cells/) | यदि true हो तो worksheet को श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणियों का समर्थन करता है)।<br/>यदि false हो तो worksheet को मानों को संग्रहीत करने के लिए उपयोग नहीं किया जाता (और यह मामला बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)।<br/>Read/write **bool**. |
| [`grouping_level_count`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | उपयोग किए गए श्रेणी समूह स्तरों की गिनती लौटाता है।<br/>बहु-स्तरीय श्रेणियों के लिए यह एक से अधिक है।<br/>Read-only **int**. |

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।

## सूचक

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | यदि संग्रह में श्रेणी मौजूद है, तो उसे लौटाएँ। अन्यथा [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) से नया चार्ट श्रेणी बनाता है और उसे संग्रह में जोड़ता है। |
| [`add(self, value)`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection/add/#any) | मान से नया [`ChartCategory`](/slides/python-net/hi/aspose.slides.charts/chartcategory) बनाता है और उसे संग्रह में जोड़ता है। |
| [`index_of(self, value)`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | निर्दिष्ट [`ChartCategory`](/slides/python-net/hi/aspose.slides.charts/chartcategory) को खोजता है और पूरी संग्रह में पहली उपस्थिति का शून्य-आधारित अनुक्रमांक लौटाता है। |
| [`remove(self, value)`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | निर्दिष्ट मान को हटाता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection/remove_at/#int) | दिए गए अनुक्रमांक पर तत्व को हटाता है। |
| [`clear(self)`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection/clear/#) | संग्रह से सभी तत्वों को हटाता है। |

### देखें
* क्लास [`ChartCategory`](/slides/python-net/hi/aspose.slides.charts/chartcategory)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)