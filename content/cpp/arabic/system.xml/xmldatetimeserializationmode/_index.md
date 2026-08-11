---
title: XmlDateTimeSerializationMode
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد كيفية معالجة قيمة الوقت عند التحويل بين السلسلة و DateTime.
type: docs
weight: 781
url: /ar/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum


Specifies how to treat the time value when converting between string and [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Local | 0 | معالجة كوقت محلي. إذا كان كائن [DateTime](../../system/datetime/) يمثل توقيت عالمي منسق (UTC)، يتم تحويله إلى الوقت المحلي. |
| Utc | 1 | معالجة كوقت UTC. إذا كان كائن [DateTime](../../system/datetime/) يمثل وقتًا محليًا، يتم تحويله إلى UTC. |
| Unspecified | 2 | معالجة كوقت محلي إذا تم تحويل [DateTime](../../system/datetime/) إلى سلسلة. إذا تم تحويل سلسلة إلى [DateTime](../../system/datetime/)، يتم التحويل إلى وقت محلي إذا تم تحديد منطقة زمنية. |
| RoundtripKind | 3 | يجب الحفاظ على معلومات المنطقة الزمنية عند التحويل. |

## انظر أيضًا

* المساحة الاسمية [System::Xml](../)
* المكتبة [Aspose.Slides](../../)