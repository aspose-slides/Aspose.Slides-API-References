---
title: ChartData class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/
---
## ChartData क्लास

Represents data used for a chart plotting.

The ChartData type exposes the following members:

## गुण

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/hi/aspose.slides.charts/chartdata/chart_data_workbook/) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किए जाने वाले सेल बनाने के लिए सेल्स फ़ैक्टरी प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/hi/aspose.slides.charts/chartdata/series/) | सीरीज़ प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IChartSeriesCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/hi/aspose.slides.charts/chartdata/series_groups/) | सीरीज़ के समूह प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories/) | मुख्य श्रेणियां प्राप्त करता है (या मुख्य और द्वितीयक दोनों श्रेणियां <br/>            यदि [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) प्रॉपर्टी false है)।<br/>            केवल-पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories/) | यदि false हो तो [`ChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories) प्रॉपर्टी None लौटाएगी और [`ChartData.categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories) प्रॉपर्टी में डेटा मुख्य और द्वितीयक दोनों सीरीज़ के लिए उपयोग किया जाता है।<br/>            यदि true हो तो [`ChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories) प्रॉपर्टी में डेटा द्वितीयक सीरीज़ के लिए उपयोग किया जाता है और [`ChartData.categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories) प्रॉपर्टी में डेटा मुख्य सीरीज़ के लिए उपयोग किया जाता है।<br/>            पढ़ें/लिखें **bool**. |
| [`secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories/) | द्वितीयक श्रेणियां प्राप्त करता है यदि [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) प्रॉपर्टी true है।<br/>            केवल-पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/hi/aspose.slides.charts/chartdata/data_source_type/) | यदि बाह्य डेटा स्रोत हो तो बाह्य वर्कबुक पथ दर्शाता है, अन्यथा None |
| [`external_workbook_path`](/slides/python-net/hi/aspose.slides.charts/chartdata/external_workbook_path/) | चार्ट का डेटा स्रोत दर्शाता है |
| [`embedded_workbook_type`](/slides/python-net/hi/aspose.slides.charts/chartdata/embedded_workbook_type/) | एंबेडेड वर्कबुक का प्रकार प्राप्त करता है।<br/>            यदि [`ChartData.data_source_type`](/slides/python-net/hi/aspose.slides.charts/chartdata/data_source_type) [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) है तो [`WorkbookType.NOT_DEFINED`](/slides/python-net/hi/aspose.slides.charts/workbooktype/NOT_DEFINED) लौटाता है।<br/>            केवल-पढ़ने योग्य [`WorkbookType`](/slides/python-net/hi/aspose.slides.charts/workbooktype). |

## विधियाँ

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/hi/aspose.slides.charts/chartdata/set_external_workbook/#str) | बाह्य वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। लक्ष्य वर्कबुक से चार्ट डेटा अपडेट किया जाएगा। |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/hi/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | बाह्य वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। |
| [`read_workbook_stream(self)`](/slides/python-net/hi/aspose.slides.charts/chartdata/read_workbook_stream/#) | आंतरिक रूप से सम्मिलित Excel वर्कबुक को एक स्ट्रीम में लिखता है। |
| [`write_workbook_stream(self, ms)`](/slides/python-net/hi/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | उपयोगकर्ता-निर्दिष्ट मान के साथ आंतरिक रूप से सम्मिलित Excel वर्कबुक को प्रारंभ करता है। |
| [`get_range(self)`](/slides/python-net/hi/aspose.slides.charts/chartdata/get_range/#) | चार्ट डेटा रेंज प्राप्त करता है। |
| [`set_range(self, formula)`](/slides/python-net/hi/aspose.slides.charts/chartdata/set_range/#str) | चार्ट डेटा रेंज सेट करता है। नई डेटा रेंज के आधार पर सीरीज़ और श्रेणियां अपडेट की जाएंगी।<br/>            यदि डेटा रेंज में सीरीज़ की मात्रा चार्ट डेटा में सीरीज़ की संख्या से अधिक है तो वर्तमान संग्रह में अंतिम सीरीज़ के समान प्रकार की अतिरिक्त सीरीज़ संग्रह के अंत में जोड़ी जाएगी। |
| [`switch_row_column(self)`](/slides/python-net/hi/aspose.slides.charts/chartdata/switch_row_column/#) | धुरी के ऊपर डेटा को अदला-बदली करें।<br/>            X धुरी पर चार्ट किया गया डेटा Y धुरी पर चलेगा और इसके विपरीत। |

### देखें भी
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)