---
title: Add()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف مخطط لغة تعريف XML (XSD) في عنوان URL المحدد إلى XmlSchemaSet.
type: docs
weight: 157
url: /ar/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) طريقة

يضيف مخطط لغة تعريف XML [Schema](../../) (XSD) في عنوان URL المحدد إلى [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | قيمة **targetNamespace** للمخطط، أو **nullptr** لاستخدام **targetNamespace** المحدد في المخطط. |
| schemaUri | const [String](../../../system/string/)\& | عنوان URL الذي يحدد المخطط المراد تحميله. |

### قيمة الإرجاع

كائن [XmlSchema](../../xmlschema/) إذا كان المخطط صالحًا. إذا لم يكن المخطط صالحًا وتم تحديد ValidationEventHandler، يتم إرجاع **nullptr** ويتم رفع حدث التحقق المناسب. وإلا يتم رمي استثناء XmlSchemaException.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) طريقة

يضيف مخطط لغة تعريف XML [Schema](../../) (XSD) الموجود في [XmlReader](../../../system.xml/xmlreader/) إلى [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | قيمة **targetNamespace** للمخطط، أو **nullptr** لاستخدام **targetNamespace** المحدد في المخطط. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | كائن [XmlReader](../../../system.xml/xmlreader/). |

### قيمة الإرجاع

كائن [XmlSchema](../../xmlschema/) إذا كان المخطط صالحًا. إذا لم يكن المخطط صالحًا وتم تحديد ValidationEventHandler، يتم إرجاع **nullptr** ويتم رفع حدث التحقق المناسب. وإلا يتم رمي استثناء XmlSchemaException.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) طريقة

يضيف جميع مخططات لغة تعريف XML [Schema](../../) (XSD) الموجودة في [XmlSchemaSet](../) إلى [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | كائن [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) طريقة

يضيف [XmlSchema](../../xmlschema/) المحدد إلى [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | كائن [XmlSchema](../../xmlschema/) لإضافته إلى [XmlSchemaSet](../). |

### قيمة الإرجاع

كائن [XmlSchema](../../xmlschema/) إذا كان المخطط صالحًا. إذا لم يكن المخطط صالحًا وتم تحديد ValidationEventHandler، يتم إرجاع **nullptr** ويتم رفع حدث التحقق المناسب. وإلا يتم رمي استثناء XmlSchemaException.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlSchema](../../xmlschema/)
* فئة [String](../../../system/string/)
* فئة [XmlSchemaSet](../)
* فئة [XmlReader](../../../system.xml/xmlreader/)
* مساحة الاسم [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)