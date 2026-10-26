---
title: ValidationType
second_title: Aspose.Slides للـ C++ مرجع API
description: يحدد نوع التحقق الذي سيتم إجراؤه.
type: docs
weight: 729
url: /ar/system.xml/validationtype/
---
## تعداد ValidationType enum


يحدد نوع التحقق الذي سيتم إجراؤه.

```cpp
enum class ValidationType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | لا يتم إجراء أي تحقق، ولا يتم إلقاء أية أخطاء تحقق. هذا الإعداد ينشئ محلّل غير تحقق يتوافق مع XML 1.0. |
| Auto | 1 | يتحقق إذا تم العثور على معلومات DTD أو مخطط. |
| DTD | 2 | يتحقق وفقًا لـ DTD. |
| XDR | 3 | يتحقق وفقًا لمخططات XML-Data Reduced (XDR)، بما في ذلك مخططات XDR المضمنة. يتم التعرف على مخططات XDR باستخدام بادئة مساحة الاسم **x-schema** أو القيمة [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | يتحقق وفقًا لمخططات لغة تعريف XML [Schema](../../system.xml.schema/) (XSD)، بما في ذلك مخططات XML المضمنة. يتم ربط مخططات XML بعناوين URI لمساحات الاسم إما باستخدام السمة **schemaLocation** أو **Schemas** المقدَّة. |

## انظر أيضًا

* النطاق [System::Xml](../)
* المكتبة [Aspose.Slides](../../)