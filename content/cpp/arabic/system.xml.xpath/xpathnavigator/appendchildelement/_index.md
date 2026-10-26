---
title: AppendChildElement()
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: ينشئ عقدة عنصر فرعي جديدة في نهاية قائمة العقد الفرعية للعقدة الحالية باستخدام بادئة نطاق الاسم والاسم المحلي وURI نطاق الاسم المحددين بالقيمة المحددة.
type: docs
weight: 1002
url: /ar/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) طريقة

Creates a new child element node at the end of the list of child nodes of the current node using the namespace prefix, local name and namespace URI specified with the value specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | بادئة نطاق الاسم للعنصر الفرعي الجديد (إن وجدت). |
| localName | [String](../../../system/string/) | الاسم المحلي للعنصر الفرعي الجديد (إن وجدت). |
| namespaceURI | [String](../../../system/string/) | URI نطاق الاسم للعنصر الفرعي الجديد (إن وجدت). [String::Empty](../../../system/string/empty/) و **nullptr** متساويان. |
| value | [String](../../../system/string/) | قيمة العنصر الفرعي الجديد. إذا تم تمرير [String::Empty](../../../system/string/empty/) أو **nullptr**، يتم إنشاء عنصر فارغ. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XPathNavigator](../)
* النطاق [System::Xml::XPath](../../)
* المكتبة [Aspose.Slides](../../../)