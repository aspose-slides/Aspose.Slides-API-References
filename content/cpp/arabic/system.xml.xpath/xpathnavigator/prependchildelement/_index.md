---
title: PrependChildElement()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ عنصرًا فرعيًا جديدًا في بداية قائمة العقد الفرعية للعنصر الحالي باستخدام بادئة المجال، الاسم المحلي، وعنوان URI للمجال المحدد بالقيمة المحددة.
type: docs
weight: 989
url: /ar/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) طريقة

ينشئ عنصرًا فرعيًا جديدًا في بداية قائمة العقد الفرعية للعنصر الحالي باستخدام بادئة المجال، الاسم المحلي، وعنوان URI للمجال المحدد بالقيمة المحددة.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | بادئة المجال للعنصر الفرعي الجديد (إن وجدت). |
| localName | [String](../../../system/string/) | الاسم المحلي للعنصر الفرعي الجديد (إن وجدت). |
| namespaceURI | [String](../../../system/string/) | عنوان URI للمجال للعنصر الفرعي الجديد (إن وجدت). [String::Empty](../../../system/string/empty/) و **nullptr** متكافئان. |
| value | [String](../../../system/string/) | قيمة العنصر الفرعي الجديد. إذا تم تمرير [String::Empty](../../../system/string/empty/) أو **nullptr**، يتم إنشاء عنصر فارغ. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XPathNavigator](../)
* النطاق [System::Xml::XPath](../../)
* المكتبة [Aspose.Slides](../../../)