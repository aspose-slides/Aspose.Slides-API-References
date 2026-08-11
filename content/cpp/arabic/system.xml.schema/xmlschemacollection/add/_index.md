---
title: Add()
second_title: Aspose.Slides للـ C++ مرجع API
description: يضيف المخطط الموجود في عنوان URL المحدد إلى مجموعة المخططات.
type: docs
weight: 40
url: /ar/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) طريقة

يضيف المخطط الموجود في عنوان URL المحدد إلى مجموعة المخططات.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | معرف URI للمساحة الاسمية المرتبط بالمخطط. بالنسبة لمخططات XML، سيكون عادةً **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | عنوان URL الذي يحدد المخطط للتحميل. |

### قيمة الإرجاع

[XmlSchema](../../xmlschema/) المضافة إلى مجموعة المخططات؛ **nullptr** إذا كان المخطط المضاف مخطط XDR أو إذا كانت هناك أخطاء تجميع في المخطط.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) طريقة

يضيف المخطط الموجود في [XmlReader](../../../system.xml/xmlreader/) إلى مجموعة المخططات.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | معرف URI للمساحة الاسمية المرتبط بالمخطط. بالنسبة لمخططات XML، سيكون عادةً **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) التي تحتوي على المخطط للإضافة. |

### قيمة الإرجاع

[XmlSchema](../../xmlschema/) المضافة إلى مجموعة المخططات؛ **nullptr** إذا كان المخطط المضاف مخطط XDR أو إذا كانت هناك أخطاء تجميع في المخطط.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يضيف المخطط الموجود في [XmlReader](../../../system.xml/xmlreader/) إلى مجموعة المخططات. يُستخدم [XmlResolver](../../../system.xml/xmlresolver/) المحدد لحل أي موارد خارجية.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | معرف URI للمساحة الاسمية المرتبط بالمخطط. بالنسبة لمخططات XML، سيكون عادةً **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) التي تحتوي على المخطط للإضافة. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) المستخدمة لحل المساحات الاسمية المشار إليها في عناصر **include** و **import** أو سمة **x-schema** (مخططات XDR). إذا كانت **nullptr**، فلن يتم حل المراجع الخارجية. |

### قيمة الإرجاع

[XmlSchema](../../xmlschema/) المضافة إلى مجموعة المخططات؛ **nullptr** إذا كان المخطط المضاف مخطط XDR أو إذا كانت هناك أخطاء تجميع في المخطط.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) طريقة

يضيف الـ[XmlSchema](../../xmlschema/) إلى المجموعة.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) للإضافة إلى المجموعة. |

### قيمة الإرجاع

الكائن [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يضيف الـ[XmlSchema](../../xmlschema/) إلى المجموعة. يُستخدم [XmlResolver](../../../system.xml/xmlresolver/) المحدد لحل أي مراجع خارجية.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) للإضافة إلى المجموعة. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) المستخدمة لحل المساحات الاسمية المشار إليها في عناصر **include** و **import**. إذا كانت **nullptr**، فلن يتم حل المراجع الخارجية. |

### قيمة الإرجاع

[XmlSchema](../../xmlschema/) المضافة إلى مجموعة المخططات.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) طريقة

يضيف جميع المساحات الاسمية المعرفة في المجموعة المعطاة (بما في ذلك المخططات المرتبطة بها) إلى هذه المجموعة.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | [XmlSchemaCollection](../) الذي تريد إضافته إلى هذه المجموعة.

## أنظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlSchema](../../xmlschema/)
* فئة [String](../../../system/string/)
* فئة [XmlSchemaCollection](../)
* فئة [XmlReader](../../../system.xml/xmlreader/)
* فئة [XmlResolver](../../../system.xml/xmlresolver/)
* نطاق [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)