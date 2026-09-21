---
title: ChartDataCell class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdatacell/
---
## ChartDataCell वर्ग

चार्ट डेटा के लिए सेल का प्रतिनिधित्व करता है।

The ChartDataCell type exposes the following members:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`row`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/row/) | सेल स्थित कार्यपत्रक की पंक्ति का सूचकांक लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`column`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/column/) | सेल स्थित कार्यपत्रक के स्तम्भ का सूचकांक लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`value`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/value/) | सेल के मान को प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **any**. |
| [`formula`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/formula/) | A1-शैली में सूत्र को प्राप्त करता है या सेट करता है। |
| [`r1c1_formula`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/r1c1_formula/) | R1C1-शैली में सूत्र को प्राप्त करता है या सेट करता है। |
| [`chart_data_worksheet`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | कार्यपत्रक को प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IChartDataWorksheet`](/slides/python-net/hi/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/is_hidden/) | निर्धारित करता है कि सेल छिपा हुआ है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`custom_number_format`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/custom_number_format/) | संख्याओं और तिथियों के लिए कस्टम प्रदर्शन फ़ॉर्मेट को प्राप्त करता है या सेट करता है। <br/>            यदि मान खाली है तो PresetNumberFormat मान उपयोग किया जाएगा।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`preset_number_format`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/preset_number_format/) | संख्याओं और तिथियों के अंतर्निहित प्रदर्शन फ़ॉर्मेट को प्राप्त करता है या सेट करता है। Preset संख्या [0..22] या [37..49] के बीच होनी चाहिए।<br/>            पढ़ने/लिखने योग्य **int**. |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/hi/aspose.slides.charts/chartdatacell/calculate/#bool) | यदि सेल में सूत्र है, तो मान उस सूत्र के आधार पर अपडेट हो जाएगा। |

### देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)