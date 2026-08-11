---
title: Add()
second_title: Aspose.Slides برای C++ مرجع API
description: اسکیمای زبان تعریف XML Schema (XSD) را در URL مشخص شده به XmlSchemaSet اضافه می‌کند.
type: docs
weight: 157
url: /fa/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) متد


یک اسکیمای زبان تعریف XML [Schema](../../) (XSD) را در URL مشخص شده به [XmlSchemaSet](../) اضافه می‌کند.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | مقدار **targetNamespace** اسکیمای هدف، یا **nullptr** برای استفاده از **targetNamespace** مشخص شده در اسکیمای. |
| schemaUri | const [String](../../../system/string/)\& | نشانی URL که اسکیمای مورد نظر برای بارگذاری را مشخص می‌کند. |

### مقدار بازگشت

اگر اسکیمای معتبر باشد، یک شیء [XmlSchema](../../xmlschema/) برگردانده می‌شود. اگر اسکیمای نامعتبر باشد و یک ValidationEventHandler تعیین شده باشد، **nullptr** برگردانده می‌شود و رویداد اعتبارسنجی مناسب فراخوانی می‌شود. در غیر این صورت، یک XmlSchemaException پرتاب می‌گردد.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) متد


یک اسکیمای زبان تعریف XML [Schema](../../) (XSD) موجود در [XmlReader](../../../system.xml/xmlreader/) را به [XmlSchemaSet](../) اضافه می‌کند.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | مقدار **targetNamespace** اسکیمای هدف، یا **nullptr** برای استفاده از **targetNamespace** مشخص شده در اسکیمای. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | شیء [XmlReader](../../../system.xml/xmlreader/). |

### مقدار بازگشت

اگر اسکیمای معتبر باشد، یک شیء [XmlSchema](../../xmlschema/) برگردانده می‌شود. اگر اسکیمای نامعتبر باشد و یک ValidationEventHandler تعیین شده باشد، **nullptr** برگردانده می‌شود و رویداد اعتبارسنجی مناسب فراخوانی می‌شود. در غیر این صورت، یک XmlSchemaException پرتاب می‌گردد.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) متد


همه اسکیمای زبان تعریف XML [Schema](../../) (XSD) موجود در [XmlSchemaSet](../) ارائه شده را به [XmlSchemaSet](../) اضافه می‌کند.

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | شیء [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) متد


[XmlSchema](../../xmlschema/) داده شده را به [XmlSchemaSet](../) اضافه می‌کند.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | شیء [XmlSchema](../../xmlschema/) برای افزودن به [XmlSchemaSet](../). |

### مقدار بازگشت

اگر اسکیمای معتبر باشد، یک شیء [XmlSchema](../../xmlschema/) برگردانده می‌شود. اگر اسکیمای نامعتبر باشد و یک ValidationEventHandler تعیین شده باشد، **nullptr** برگردانده می‌شود و رویداد اعتبارسنجی مناسب فراخوانی می‌شود. در غیر این صورت، یک XmlSchemaException پرتاب می‌گردد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlSchema](../../xmlschema/)
* کلاس [String](../../../system/string/)
* کلاس [XmlSchemaSet](../)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* فضای نام [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)