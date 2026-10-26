---
title: Contains()
second_title: مرجع API Aspose.Slides برای C++
description: نشان می‌دهد که آیا XmlSchemaObject مشخص شده در XmlSchemaObjectCollection قرار دارد.
type: docs
weight: 92
url: /fa/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) متد

نشان می‌دهد که [XmlSchemaObject](../../xmlschemaobject/) مشخص شده در [XmlSchemaObjectCollection](../) موجود است.

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | متغیر [XmlSchemaObject](../../xmlschemaobject/). |

### مقدار بازگشت

**true** اگر نام معتبر مشخص شده در مجموعه باشد؛ در غیر این صورت **false** بازگردانده می‌شود. اگر **nullptr** فراهم شده باشد، **false** بازگردانده می‌شود زیرا نام معتبری با نام تهی وجود ندارد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlSchemaObject](../../xmlschemaobject/)
* کلاس [XmlSchemaObjectCollection](../)
* فضای‌نام [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)