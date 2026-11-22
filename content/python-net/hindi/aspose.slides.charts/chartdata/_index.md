---
title: ChartData class
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/
---
## ChartData वर्ग

चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा का प्रतिनिधित्व करता है।

ChartData प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/hi/aspose.slides.charts/chartdata/chart_data_workbook/) | चार्ट श्रृंखला या वर्गों के उपयोग के लिए कोशिकाएँ बनाने के लिए कोशिका फ़ैक्ट्री प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/hi/aspose.slides.charts/chartdata/series/) | श्रृंखला प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IChartSeriesCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/hi/aspose.slides.charts/chartdata/series_groups/) | श्रृंखला के समूह प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories/) | प्राथमिक वर्ग (या अगर [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) गुण false हो तो प्राथमिक और द्वितीयक वर्ग दोनों) प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories/) | यदि false हो तो [`ChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories) गुण None लौटाता है और [`ChartData.categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories) गुण में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखला के लिए उपयोग किया जाता है।<br/>            यदि true हो तो [`ChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories) गुण में डेटा द्वितीयक श्रृंखला के लिए उपयोग किया जाता है और [`ChartData.categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories) गुण में डेटा प्राथमिक श्रृंखला के लिए उपयोग किया जाता है।<br/>            पढ़ें/लिखें **bool**. |
| [`secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories/) | यदि [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) गुण true हो तो द्वितीयक वर्ग प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/hi/aspose.slides.charts/chartdata/data_source_type/) | यदि बाहरी डेटा स्रोत है तो बाहरी कार्यपुस्तिका पथ दर्शाता है, अन्यथा None |
| [`external_workbook_path`](/slides/python-net/hi/aspose.slides.charts/chartdata/external_workbook_path/) | चार्ट का डेटा स्रोत दर्शाता है |
| [`embedded_workbook_type`](/slides/python-net/hi/aspose.slides.charts/chartdata/embedded_workbook_type/) | एम्बेडेड कार्यपुस्तिका का प्रकार प्राप्त करता है।<br/>            यदि [`ChartData.data_source_type`](/slides/python-net/hi/aspose.slides.charts/chartdata/data_source_type) है तो [`WorkbookType.NOT_DEFINED`](/slides/python-net/hi/aspose.slides.charts/workbooktype/NOT_DEFINED) लौटाता है<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            केवल-पढ़ने योग्य [`WorkbookType`](/slides/python-net/hi/aspose.slides.charts/workbooktype). |

## विधियाँ

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/hi/aspose.slides.charts/chartdata/set_external_workbook/#str) | चार्ट के डेटा स्रोत के रूप में बाहरी कार्यपुस्तिका सेट करता है। लक्ष्य कार्यपुस्तिका से चार्ट डेटा अद्यतन किया जाएगा। |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/hi/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | चार्ट के डेटा स्रोत के रूप में बाहरी कार्यपुस्तिका सेट करता है। |
| [`read_workbook_stream(self)`](/slides/python-net/hi/aspose.slides.charts/chartdata/read_workbook_stream/#) | आंतरिक रूप से संलग्न Excel कार्यपुस्तिका को एक स्ट्रीम में लिखता है। |
| [`write_workbook_stream(self, ms)`](/slides/python-net/hi/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | उपयोगकर्ता-निर्दिष्ट मान के साथ आंतरिक रूप से संलग्न Excel कार्यपुस्तिका को आरंभ करता है। |
| [`get_range(self)`](/slides/python-net/hi/aspose.slides.charts/chartdata/get_range/#) | चार्ट डेटा रेंज प्राप्त करता है। |
| [`set_range(self, formula)`](/slides/python-net/hi/aspose.slides.charts/chartdata/set_range/#str) | चार्ट डेटा रेंज सेट करता है। नई डेटा रेंज के आधार पर श्रृंखला और वर्ग अद्यतन किए जाएंगे।<br/>            यदि डेटा रेंज में श्रृंखला की संख्या चार्ट डेटा में श्रृंखला की संख्या से अधिक है तो वर्तमान संग्रह में अंतिम श्रृंखला के समान प्रकार की अतिरिक्त श्रृंखला संग्रह के अंत में जोड़ी जाएगी। |
| [`refresh_data(self)`](/slides/python-net/hi/aspose.slides.charts/chartdata/refresh_data/#) | स्रोत कार्यपुस्तिका से पुनः लोड करके चार्ट डेटा को रीफ़्रेश करता है। |
| [`switch_row_column(self)`](/slides/python-net/hi/aspose.slides.charts/chartdata/switch_row_column/#) | अक्ष के ऊपर डेटा बदलें।<br/>            X अक्ष पर चार्ट किया गया डेटा Y अक्ष पर चलेगा और इसके विपरीत। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)