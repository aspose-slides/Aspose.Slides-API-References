---
title: Read()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يقوم بقراءة مخطط XML من الـ IO::TextReader المقدم."
type: docs
weight: 365
url: /ar/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) طريقة

يقرأ XML [Schema](../../) من [IO::TextReader](../../../system.io/textreader/) المقدم.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | ال[IO::TextReader](../../../system.io/textreader/) الذي يحتوي على XML [Schema](../../) للقراءة. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | معالج حدث التحقق الذي يتلقى معلومات حول أخطاء بنية XML [Schema](../../). |

### قيمة الإرجاع

الكائن [XmlSchema](../) الذي يمثل XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) طريقة

يقرأ XML [Schema](../../) من الدفق المقدم.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | دفق البيانات المقدم. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | معالج حدث التحقق الذي يتلقى معلومات حول أخطاء بنية XML [Schema](../../). |

### قيمة الإرجاع

الكائن [XmlSchema](../) الذي يمثل XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) طريقة


يقرأ XML [Schema](../../) من [XmlReader](../../../system.xml/xmlreader/) المقدم.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | ال[XmlReader](../../../system.xml/xmlreader/) الذي يحتوي على XML [Schema](../../) للقراءة. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | معالج حدث التحقق الذي يتلقى معلومات حول أخطاء بنية XML [Schema](../../). |

### قيمة الإرجاع

الكائن [XmlSchema](../) الذي يمثل XML [Schema](../../).

## راجع أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ValidationEventHandler](../../validationeventhandler/)
* فئة [XmlSchema](../)
* فئة [TextReader](../../../system.io/textreader/)
* فئة [Stream](../../../system.io/stream/)
* فئة [XmlReader](../../../system.xml/xmlreader/)
* مسافة اسم [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)