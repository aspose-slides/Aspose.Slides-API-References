---
title: ConformanceLevel
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد مقدار فحص الإدخال أو الإخراج الذي تقوم به كائنات XmlReader و XmlWriter.
type: docs
weight: 625
url: /ar/system.xml/conformancelevel/
---
## ConformanceLevel enum


يحدد مقدار فحص الإدخال أو الإخراج الذي تقوم به كائنات [XmlReader](../xmlreader/) و [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | 0 | الكائن [XmlReader](../xmlreader/) أو الكائن [XmlWriter](../xmlwriter/) يكتشف تلقائيًا ما إذا كان يجب إجراء فحص على مستوى المستند أو على مستوى الجزء، ويقوم بالفحص المناسب. إذا كنت تقوم بلف كائن [XmlReader](../xmlreader/) أو كائن [XmlWriter](../xmlwriter/) آخر، فإن الكائن الخارجي لا يقوم بأي تحقق إضافي من التوافق. يُترك التحقق من التوافق للكيان الأساسي. |
| Fragment | 1 | بيانات XML هي [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities)، كما تعرفها W3C. تمثل هذه المستوى من التوافق مستند XML قد لا يحتوي على عنصر جذري ولكنه سليم الشكل بخلاف ذلك. يضمن هذا المستوى من الفحص أن التدفق الذي يتم قراءته أو كتابته يمكن أن يستهلكه أي معالج كـ [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | بيانات XML تتوافق مع القواعد الخاصة بـ [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) سليم الشكل، كما تعرفها W3C. يضمن هذا المستوى من الفحص أن التدفق الذي يتم قراءته أو كتابته يمكن أن يستهلكه أي معالج كـ [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## انظر أيضاً

* النطاق [System::Xml](../)
* المكتبة [Aspose.Slides](../../)