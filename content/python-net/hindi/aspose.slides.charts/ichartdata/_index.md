---
title: IChartData class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/
---
## IChartData क्लास

एक चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा का प्रतिनिधित्व करता है।

IChartData प्रकार निम्नलिखित सदस्य उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/hi/aspose.slides.charts/ichartdata/chart_data_workbook/) | चार्ट श्रृंखला या श्रेणियों के लिए उपयोग किए जाने वाले कोशिकाओं को बनाने के लिए सेल फैक्ट्री प्राप्त करता है।<br/>            केवल पढ़ने योग्य [`IChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/hi/aspose.slides.charts/ichartdata/series/) | श्रृंखलाएँ प्राप्त करता है।<br/>            केवल पढ़ने योग्य [`IChartSeriesCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/hi/aspose.slides.charts/ichartdata/series_groups/) | श्रृंखलाओं के समूह प्राप्त करता है।<br/>            केवल पढ़ने योग्य [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories/) | मुख्य श्रेणियाँ प्राप्त करता है (या दोनों मुख्य और द्वितीयक श्रेणियाँ <br/>            यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) प्रॉपर्टी false है)।<br/>            केवल पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories/) | यदि false है तो [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) प्रॉपर्टी None लौटाएगी और [`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) प्रॉपर्टी में डेटा मुख्य और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है।<br/>            यदि true है तो [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) प्रॉपर्टी में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है और [`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) प्रॉपर्टी में डेटा मुख्य श्रृंखलाओं के लिए उपयोग किया जाता है।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories/) | यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) प्रॉपर्टी true है तो द्वितीयक श्रेणियाँ प्राप्त करता है।<br/>            केवल पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/hi/aspose.slides.charts/ichartdata/data_source_type/) | चार्ट के डेटा स्रोत का प्रतिनिधित्व करता है |
| [`external_workbook_path`](/slides/python-net/hi/aspose.slides.charts/ichartdata/external_workbook_path/) | यदि डेटा स्रोत बाहरी है तो बाहरी वर्कबुक पथ का प्रतिनिधित्व करता है, अन्यथा None |
| [`embedded_workbook_type`](/slides/python-net/hi/aspose.slides.charts/ichartdata/embedded_workbook_type/) | एम्बेडेड वर्कबुक के प्रकार को प्राप्त करता है।<br/>            यदि [`IChartData.data_source_type`](/slides/python-net/hi/aspose.slides.charts/ichartdata/data_source_type) [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) है तो [`WorkbookType.NOT_DEFINED`](/slides/python-net/hi/aspose.slides.charts/workbooktype/NOT_DEFINED) लौटाता है।<br/>            केवल पढ़ने योग्य [`WorkbookType`](/slides/python-net/hi/aspose.slides.charts/workbooktype). |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/set_external_workbook/#str) | बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। चार्ट डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा। |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। |
| [`read_workbook_stream(self)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/read_workbook_stream/#) | आंतरिक रूप से निहित Excel वर्कबुक को मेमोरी में स्ट्रीम में लिखता है। |
| [`write_workbook_stream(self, ms)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | उपयोगकर्ता-निर्दिष्ट मान के साथ आंतरिक रूप से निहित Excel वर्कबुक को प्रारंभ करता है। |
| [`set_range(self, formula)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/set_range/#str) | चार्ट डेटा रेंज सेट करें। नई डेटा रेंज के आधार पर श्रृंखलाएँ और श्रेणियाँ अपडेट की जाएँगी।<br/>            यदि डेटा रेंज में श्रृंखलाओं की संख्या चार्ट डेटा में श्रृंखलाओं की संख्या से अधिक है तो वर्तमान संग्रह में अंतिम श्रृंखला के समान प्रकार की अतिरिक्त श्रृंखलाएँ संग्रह के अंत में जोड़ी जाएँगी। |
| [`get_range(self)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/get_range/#) | चार्ट डेटा रेंज प्राप्त करता है। |
| [`switch_row_column(self)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/switch_row_column/#) | धुरी के ऊपर डेटा को स्वैप करें।<br/>            X धुरी पर चार्ट किया गया डेटा Y धुरी पर चलेगा और इसके विपरीत। |

### देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)