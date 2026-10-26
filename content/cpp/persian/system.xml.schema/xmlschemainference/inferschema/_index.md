---
title: InferSchema()
second_title: Aspose.Slides برای C++ – مرجع API
description: از سند XML موجود در شیء XmlReader مشخص‌شده، یک طرح‌نامه XML Schema Definition Language (XSD) را استنتاج می‌کند.
type: docs
weight: 66
url: /fa/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method


یک طرح‌نامه XML [Schema](../../) Definition Language (XSD) را از سند XML موجود در شیء [XmlReader](../../../system.xml/xmlreader/) مشخص‌شده استنتاج می‌کند.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | شیء [XmlReader](../../../system.xml/xmlreader/) که شامل سند XML برای استنتاج یک طرح‌نامه است. |

### مقدار بازگشتی

شیء [XmlSchemaSet](../../xmlschemaset/) که شامل طرح‌نامه‌های استنتاج‌شده است.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method


یک طرح‌نامه XML [Schema](../../) Definition Language (XSD) را از سند XML موجود در شیء [XmlReader](../../../system.xml/xmlreader/) مشخص‌شده استنتاج می‌کند و طرح‌نامه استنتاج‌شده را با استفاده از یک طرح‌نامه موجود در شیء [XmlSchemaSet](../../xmlschemaset/) که فضای‌نام هدف یکسانی دارد، تصحیح می‌نماید.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | شیء [XmlReader](../../../system.xml/xmlreader/) که شامل سند XML برای استنتاج یک طرح‌نامه است. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | شیء [XmlSchemaSet](../../xmlschemaset/) که شامل یک طرح‌نامه موجود است و برای تصحیح طرح‌نامه استنتاج‌شده استفاده می‌شود. |

### مقدار بازگشتی

شیء [XmlSchemaSet](../../xmlschemaset/) که شامل طرح‌نامه‌های استنتاج‌شده است.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlSchemaSet](../../xmlschemaset/)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* کلاس [XmlSchemaInference](../)
* فضای‌نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)