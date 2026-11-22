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
| [`use_cell`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/use_cell/) | यदि सत्य है तो AsCell गुण वास्तविक है। अन्य शब्दों में, worksheet का उपयोग श्रेणी संग्रहीत करने के लिए किया जाता है <br/>            storing category (this case supports a multi-level category).<br/>            यदि गलत है तो AsLiteral गुण वास्तविक है। अन्य शब्दों में, worksheet श्रेणी संग्रहीत करने के लिए उपयोग नहीं किया जाता <br/>            for storing category (and this case doesn't support a multi-level categories).<br/>            केवल-पढ़ने योग्य **bool**. |
| [`as_cell`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/as_cell/) | IChartDataCell ऑब्जेक्ट को प्राप्त करता है या सेट करता है।<br/>            यदि श्रेणी बहु-स्तरीय है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट का उपयोग किया जाता है।<br/>            पढ़ें/लिखें [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/as_literal/) | यदि UseCell गलत है तो AsLiteral को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें **any**. |
| [`value`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/value/) | यदि UseCell सत्य है तो यह गुण AsCell.Value गुण का प्रतिनिधित्व करता है।<br/>            यदि UseCell गलत है तो यह गुण AsLiteral गुण का प्रतिनिधित्व करता है।<br/>            पढ़ें/लिखें **any**. |
| [`cached_value`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/cached_value/) | चार्ट श्रेणी का संग्रहीत मान प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`ICachedChartValue`](/slides/python-net/hi/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/grouping_levels/) | चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर।<br/>            Multi-level category contain more then one grouping level.<br/>            Grouping levels indexing is zero-based.<br/>            केवल-पढ़ने योग्य [`IChartCategoryLevelsManager`](/slides/python-net/hi/aspose.slides.charts/ichartcategorylevelsmanager). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`remove(self)`](/slides/python-net/hi/aspose.slides.charts/ichartcategory/remove/#) | श्रेणी को चार्ट से हटाता है। |

### देखें भी
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)