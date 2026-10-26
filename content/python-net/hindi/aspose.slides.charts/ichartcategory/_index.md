---
title: IChartCategory class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartcategory/
---
## IChartCategory क्लास

चार्ट श्रेणियों का प्रतिनिधित्व करता है।

IChartCategory प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`use_cell`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/use_cell/) | यदि सत्य है तो AsCell property वास्तविक है। दूसरे शब्दों में, worksheet का उपयोग <br/>            श्रेणी को संग्रहीत करने के लिए किया जाता है (यह केस बहु-स्तरीय श्रेणी को समर्थन करता है).<br/>            यदि असत्य है तो AsLiteral property वास्तविक है। दूसरे शब्दों में, worksheet का उपयोग श्रेणी को संग्रहीत करने के लिए नहीं किया जाता <br/>            (और यह केस बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)।<br/>            केवल पढ़ने योग्य **bool**. |
| [`as_cell`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/as_cell/) | फ़िर लौटाता है या सेट करता है IChartDataCell ऑब्जेक्ट।<br/>            यदि श्रेणी बहु-स्तरीय है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट उपयोग किया जाता है।<br/>            पढ़ना/लिखना [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/as_literal/) | यदि UseCell असत्य है तो AsLiteral को लौटाता है या सेट करता है।<br/>            पढ़ना/लिखना **any**. |
| [`value`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/value/) | यदि UseCell सत्य है तो यह गुण AsCell.Value property को दर्शाता है।<br/>            यदि UseCell असत्य है तो यह गुण AsLiteral property को दर्शाता है।<br/>            पढ़ना/लिखना **any**. |
| [`grouping_levels`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/grouping_levels/) | चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर।<br/>            बहु-स्तरीय श्रेणी में एक से अधिक समूह स्तर होते हैं।<br/>            समूह स्तरों की अनुक्रमण शून्य-आधारित है।<br/>            केवल पढ़ने योग्य [`IChartCategoryLevelsManager`](/slides/python-net/hi/aspose.slides.charts/ichartcategorylevelsmanager). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`remove(self)`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/remove/#) | चार्ट से श्रेणी को हटाता है। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)