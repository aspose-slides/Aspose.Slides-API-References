---
title: get_SchemaInfo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد معلومات المخطط التي تم تعيينها للعقدة الحالية نتيجةً للتحقق من صحة المخطط.
type: docs
weight: 196
url: /ar/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() طريقة


يعيد معلومات المخطط التي تم تعيينها للعقدة الحالية نتيجةً للتحقق من صحة المخطط.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### قيمة الإرجاع

كائن IXmlSchemaInfo يحتوي على معلومات المخطط للعقدة الحالية. يمكن تعيين معلومات [Schema](../../../system.xml.schema/) على العناصر أو السمات أو على عقد النص ذات قيمة غير فارغة [XmlReader::get_ValueType](../get_valuetype/). إذا لم تكن العقدة الحالية أحد أنواع العقد المذكورة أعلاه، أو إذا لم تقم المثيلة [XmlReader](../) بالإبلاغ عن معلومات المخطط، فإن هذه الطريقة تُعيد **nullptr**. إذا استُدعيت هذه الطريقة من كائن [XmlTextReader](../../xmltextreader/) أو كائن [XmlValidatingReader](../../xmlvalidatingreader/)، فإن هذه الطريقة دائمًا تُعيد **nullptr**. هذه التطبيقات [XmlReader](../) لا تكشف عن معلومات المخطط من خلال طريقة get_SchemaInfo.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* فئة [XmlReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)