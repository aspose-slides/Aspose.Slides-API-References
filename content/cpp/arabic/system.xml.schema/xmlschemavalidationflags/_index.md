---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides للـ C++ مرجع API
description: يحدد خيارات التحقق من صحة المخطط المستخدمة من قبل فئتي XmlSchemaValidator و XmlReader.
type: docs
weight: 1054
url: /ar/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags تعداد

Specifies schema validation options used by the [XmlSchemaValidator](../xmlschemavalidator/) and [XmlReader](../../system.xml/xmlreader/) classes.

```cpp
enum class XmlSchemaValidationFlags
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | عدم معالجة قيود الهوية، المخططات المضمنة، تلميحات موقع المخطط، أو الإبلاغ عن تحذيرات التحقق من صحة المخطط. |
| ProcessInlineSchema | 1 | معالجة المخططات المضمنة التي تم العثور عليها أثناء التحقق. |
| ProcessSchemaLocation | 2 | معالجة تلميحات موقع المخطط (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) التي تم العثور عليها أثناء التحقق. |
| ReportValidationWarnings | 4 | الإبلاغ عن تحذيرات التحقق من صحة المخطط التي تم العثور عليها أثناء التحقق. |
| ProcessIdentityConstraints | 8 | معالجة قيود الهوية (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) التي تم العثور عليها أثناء التحقق. |
| AllowXmlAttributes | 16 | السماح بسمات xml:* حتى إذا لم يتم تعريفها في المخطط. سيتم التحقق من صحة السمات بناءً على نوع البيانات الخاص بها. |

## انظر أيضًا

* النطاق [System::Xml::Schema](../)
* المكتبة [Aspose.Slides](../../)