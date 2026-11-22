---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartcategory/
---
## ChartCategory वर्ग

चार्ट श्रेणियों का प्रतिनिधित्व करता है।

ChartCategory प्रकार निम्न सदस्य प्रदान करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`use_cell`](/slides/python-net/hi/aspose.slides.charts/chartcategory/use_cell/) | यदि true है तो AsCell गुण वास्तविक है। दूसरे शब्दों में, worksheet का उपयोग <br/>            श्रेणी संग्रहीत करने के लिए किया जाता है (यह केस मल्टी-लेवल श्रेणी का समर्थन करता है)।<br/>            यदि false है तो AsLiteral गुण वास्तविक है। दूसरे शब्दों में, worksheet का उपयोग नहीं किया जाता है <br/>            श्रेणी संग्रहीत करने के लिए (और यह केस मल्टी-लेवल श्रेणियों का समर्थन नहीं करता)।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`as_cell`](/slides/python-net/hi/aspose.slides.charts/chartcategory/as_cell/) | IChartDataCell object को लौटाता या सेट करता है।<br/>            यदि श्रेणी मल्टी-लेवल है तो स्तर "0" के लिए IChartDataCell object का उपयोग किया जाता है।<br/>            पढ़ने/लिखने योग्य [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/hi/aspose.slides.charts/chartcategory/as_literal/) | AsLiteral object को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **any**. |
| [`value`](/slides/python-net/hi/aspose.slides.charts/chartcategory/value/) | यदि UseCell true है तो यह गुण AsCell.Value गुण को दर्शाता है।<br/>            यदि UseCell false है तो यह गुण AsLiteral गुण को दर्शाता है।<br/>            पढ़ने/लिखने योग्य **any**. |
| [`grouping_levels`](/slides/python-net/hi/aspose.slides.charts/chartcategory/grouping_levels/) | चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर।<br/>            मल्टी-लेवल श्रेणी में अधिक से अधिक एक समूह स्तर हो सकता है।<br/>            समूह स्तरों का अनुक्रमण शून्य-आधारित है।<br/>            केवल-पढ़ने योग्य [`IChartCategoryLevelsManager`](/slides/python-net/hi/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/hi/aspose.slides.charts/chartcategory/cached_value/) | एक चार्ट श्रेणी का कैश्ड मान प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`ICachedChartValue`](/slides/python-net/hi/aspose.slides.charts/icachedchartvalue). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`remove(self)`](/slides/python-net/hi/aspose.slides.charts/chartcategory/remove/#) | श्रेणी को चार्ट से हटाता है। |


### संबंधित देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)