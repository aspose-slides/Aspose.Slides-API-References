---
title: IChartData class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/
---
## IChartData वर्ग

चार्ट प्लॉटिंग के लिए उपयोग किए जाने वाले डेटा का प्रतिनिधित्व करता है।

IChartData प्रकार निम्नलिखित सदस्य दिखाता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/hi/aspose.slides.charts/ichartdata/chart_data_workbook/) | चार्ट सीरीज या श्रेणियों के लिए उपयोग किए जाने वाले सेल बनाने के लिए सेल फ़ैक्टरी प्राप्त करता है।<br/>केवल पढ़ने योग्य [`IChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/hi/aspose.slides.charts/ichartdata/series/) | सीरीज प्राप्त करता है।<br/>केवल पढ़ने योग्य [`IChartSeriesCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/hi/aspose.slides.charts/ichartdata/series_groups/) | सीरीज के समूह प्राप्त करता है।<br/>केवल पढ़ने योग्य [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories/) | प्राथमिक श्रेणियां प्राप्त करता है (या दोनों प्राथमिक और द्वितीयक श्रेणियां <br/>यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) प्रॉपर्टी गलत है)।<br/>केवल पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories/) | यदि false है तो [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) प्रॉपर्टी None लौटाती है और डेटा <br/>[`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) प्रॉपर्टी में प्राथमिक और द्वितीयक दोनों सीरीज के लिए उपयोग की जाती है।<br/>यदि true है तो डेटा [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) प्रॉपर्टी में द्वितीयक सीरीज के लिए और डेटा <br/>[`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) प्रॉपर्टी में प्राथमिक सीरीज के लिए उपयोग की जाती है।<br/>पढ़ें/लिखें **bool**. |
| [`secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories/) | द्वितीयक श्रेणियां प्राप्त करता है यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) प्रॉपर्टी true है।<br/>केवल पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/hi/aspose.slides.charts/ichartdata/data_source_type/) | चार्ट का डेटा स्रोत दर्शाता है। |
| [`external_workbook_path`](/slides/python-net/hi/aspose.slides.charts/ichartdata/external_workbook_path/) | डेटा स्रोत बाह्य होने पर बाहरी वर्कबुक पथ दर्शाता है, अन्यथा None। |
| [`embedded_workbook_type`](/slides/python-net/hi/aspose.slides.charts/ichartdata/embedded_workbook_type/) | एम्बेडेड वर्कबुक का प्रकार प्राप्त करता है।<br/>यदि [`IChartData.data_source_type`](/slides/python-net/hi/aspose.slides.charts/ichartdata/data_source_type) [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) है तो [`WorkbookType.NOT_DEFINED`](/slides/python-net/hi/aspose.slides.charts/workbooktype/NOT_DEFINED) लौटाता है।<br/>केवल पढ़ने योग्य [`WorkbookType`](/slides/python-net/hi/aspose.slides.charts/workbooktype). |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/set_external_workbook/#str) | चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। लक्ष्य वर्कबुक से चार्ट डेटा अपडेट किया जाएगा। |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। |
| [`read_workbook_stream(self)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/read_workbook_stream/#) | आंतरिक रूप से शामिल एक्सेल वर्कबुक को इन-मेमोरी स्ट्रीम में लिखता है। |
| [`write_workbook_stream(self, ms)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | आंतरिक रूप से शामिल एक्सेल वर्कबुक को उपयोगकर्ता-निर्दिष्ट मान से प्रारम्भ करता है। |
| [`set_range(self, formula)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/set_range/#str) | चार्ट डेटा रेंज सेट करता है। सीरीज और श्रेणियां नई डेटा रेंज के आधार पर अपडेट होंगी।<br/>यदि डेटा रेंज में सीरीज की मात्रा चार्ट डेटा में सीरीज की संख्या से अधिक है तो मौजूदा संग्रह में अंत में अंतिम सीरीज के समान प्रकार की अतिरिक्त सीरीज जोड़ी जाएगी। |
| [`get_range(self)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/get_range/#) | चार्ट डेटा रेंज प्राप्त करता है। |
| [`switch_row_column(self)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/switch_row_column/#) | डेटा को अक्ष के ऊपर स्वैप करता है।<br/>X-अक्ष पर चार्ट किया गया डेटा Y-अक्ष पर चलेगा और इसके विपरीत। |
| [`refresh_data(self)`](/slides/python-net/hi/aspose.slides.charts/ichartdata/refresh_data/#) | सोर्स वर्कबुक से पुनः लोड करके चार्ट डेटा को रिफ्रेश करता है। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)