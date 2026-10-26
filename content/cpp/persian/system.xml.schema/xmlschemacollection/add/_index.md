---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: اسکیما را که توسط URL داده شده قرار دارد به مجموعهٔ اسکیماها اضافه می‌کند.
type: docs
weight: 40
url: /fa/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) متد

اسکیما را که توسط URL داده شده قرار دارد به مجموعه اسکیماها اضافه می‌کند.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI فضای نام مرتبط با اسکیما. برای XML Schemas، معمولاً **targetNamespace** خواهد بود. |
| uri | const [String](../../../system/string/)\& | URLی که اسکیما را برای بارگذاری مشخص می‌کند. |

### مقدار بازگشت

[XmlSchema](../../xmlschema/) اضافه‌شده به مجموعه اسکیماها؛ **nullptr** اگر اسکیما اضافه‌شده یک اسکیما XDR باشد یا اگر خطاهای کامپایل در اسکیما وجود داشته باشد.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) متد

اسکیما موجود در [XmlReader](../../../system.xml/xmlreader/) را به مجموعه اسکیماها اضافه می‌کند.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI فضای نام مرتبط با اسکیما. برای XML Schemas، معمولاً **targetNamespace** خواهد بود. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) شامل اسکیما برای اضافه کردن. |

### مقدار بازگشت

[XmlSchema](../../xmlschema/) اضافه‌شده به مجموعه اسکیماها؛ **nullptr** اگر اسکیما اضافه‌شده یک اسکیما XDR باشد یا اگر خطاهای کامپایل در اسکیما وجود داشته باشد.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) متد

اسکیما موجود در [XmlReader](../../../system.xml/xmlreader/) را به مجموعه اسکیماها اضافه می‌کند. [XmlResolver](../../../system.xml/xmlresolver/) مشخص‌شده برای حل هر منبع خارجی استفاده می‌شود.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI فضای نام مرتبط با اسکیما. برای XML Schemas، معمولاً **targetNamespace** خواهد بود. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) شامل اسکیما برای اضافه کردن. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) استفاده‌شده برای حل فضاهای نام اشاره‌شده در عناصر **include** و **import** یا ویژگی **x-schema** (اسکیماهای XDR). اگر این مقدار **nullptr** باشد، ارجاع‌های خارجی حل نمی‌شوند. |

### مقدار بازگشت

[XmlSchema](../../xmlschema/) اضافه‌شده به مجموعه اسکیماها؛ **nullptr** اگر اسکیما اضافه‌شده یک اسکیما XDR باشد یا اگر خطاهای کامپایل در اسکیما وجود داشته باشد.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) متد

[XmlSchema](../../xmlschema/) را به مجموعه اضافه می‌کند.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) برای اضافه شدن به مجموعه. |

### مقدار بازگشت

شیء [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) متد

[XmlSchema](../../xmlschema/) را به مجموعه اضافه می‌کند. [XmlResolver](../../../system.xml/xmlresolver/) مشخص‌شده برای حل هر ارجاع خارجی استفاده می‌شود.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) برای اضافه شدن به مجموعه. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) استفاده‌شده برای حل فضاهای نام اشاره‌شده در عناصر **include** و **import**. اگر این مقدار **nullptr** باشد، ارجاع‌های خارجی حل نمی‌شوند. |

### مقدار بازگشت

[XmlSchema](../../xmlschema/) اضافه‌شده به مجموعه اسکیماها.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) متد

تمام فضاهای نام تعریف‌شده در مجموعه‌ی داده شده (به همراه اسکیماهای مرتبط) را به این مجموعه اضافه می‌کند.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | [XmlSchemaCollection](../) که می‌خواهید به این مجموعه اضافه کنید. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)