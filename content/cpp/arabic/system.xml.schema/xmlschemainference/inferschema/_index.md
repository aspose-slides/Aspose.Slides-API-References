---
title: InferSchema()
second_title: Aspose.Slides للغة C++ مرجع API
description: يستنتج مخطط لغة تعريف مخطط XML (XSD) من مستند XML الموجود في كائن XmlReader المحدد.
type: docs
weight: 66
url: /ar/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) طريقة


يستنتج مخطط XML [Schema](../../) Definition Language (XSD) من مستند XML الموجود في كائن [XmlReader](../../../system.xml/xmlreader/) المحدد.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | كائن [XmlReader](../../../system.xml/xmlreader/) يحتوي على مستند XML لاستخراج مخطط منه. |

### Return Value

كائن [XmlSchemaSet](../../xmlschemaset/) يحتوي على المخططات المستنتجة.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) طريقة


يستنتج مخطط XML [Schema](../../) Definition Language (XSD) من مستند XML الموجود في كائن [XmlReader](../../../system.xml/xmlreader/) المحدد، ويُحسّن المخطط المستنتج باستخدام مخطط موجود في كائن [XmlSchemaSet](../../xmlschemaset/) المحدد بنفس مساحة الاسم الهدف.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | كائن [XmlReader](../../../system.xml/xmlreader/) يحتوي على مستند XML لاستخراج مخطط منه. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | كائن [XmlSchemaSet](../../xmlschemaset/) يحتوي على مخطط موجود يُستخدم لتحسين المخطط المستنتج. |

### Return Value

كائن [XmlSchemaSet](../../xmlschemaset/) يحتوي على المخططات المستنتجة.

## راجع أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlSchemaSet](../../xmlschemaset/)
* فئة [XmlReader](../../../system.xml/xmlreader/)
* فئة [XmlSchemaInference](../)
* مساحة الاسم [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)