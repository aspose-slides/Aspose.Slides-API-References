---
title: Reprocess()
second_title: مرجع API Aspose.Slides برای C++
description: طرح تعریف زبان XML Schema (XSD) که قبلاً در XmlSchemaSet موجود است را پردازش مجدد می‌کند.
type: docs
weight: 222
url: /fa/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) متد


بار دیگر یک طرح تعریف زبان XML [Schema](../../) (XSD) که قبلاً در [XmlSchemaSet](../) موجود است را پردازش می‌کند.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | طرح برای پردازش مجدد. |

### مقدار بازگشت

در صورت معتبر بودن طرح، یک شیء [XmlSchema](../../xmlschema/) برگردانده می‌شود. اگر طرح معتبر نباشد و یک ValidationEventHandler مشخص شده باشد، **nullptr** برگردانده می‌شود و رویداد معتبرسازی مناسب فراخوانی می‌شود. در غیر این صورت، یک XmlSchemaException پرتاب می‌شود.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlSchema](../../xmlschema/)
* کلاس [XmlSchemaSet](../)
* فضای نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)