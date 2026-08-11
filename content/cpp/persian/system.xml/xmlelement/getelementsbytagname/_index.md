---
title: GetElementsByTagName()
second_title: مرجع API Aspose.Slides برای C++
description: "یک XmlNodeList را برمی‌گرداند که شامل فهرستی از تمام عناصر فرزندی است که با XmlElement::get_Name مشخص شده مطابقت دارد."
type: docs
weight: 287
url: /fa/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) متد

یک [XmlNodeList](../../xmlnodelist/) را بر می‌گرداند که شامل فهرستی از تمام عناصر فرزندی است که با [XmlElement::get_Name](../get_name/) مشخص شده مطابقت دارند.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | برچسب نام برای مقایسه. این یک نام معتبر است. با مقدار **get_Name** گرهٔ مطابقت‌دهنده مقایسه می‌شود. علامت ستاره (*) مقدار ویژه‌ای است که با تمام برچسب‌ها مطابقت دارد. |

### مقدار برگشتی

یک [XmlNodeList](../../xmlnodelist/) شامل فهرستی از تمام گره‌های مطابق. اگر گرهٔ مطابقی وجود نداشته باشد، فهرست خالی است.

## XmlElement::GetElementsByTagName(String, String) متد

یک [XmlNodeList](../../xmlnodelist/) را بر می‌گرداند که شامل فهرستی از تمام عناصر فرزندی است که با مقادیر [XmlElement::get_LocalName](../get_localname/) و [XmlElement::get_NamespaceURI](../get_namespaceuri/) مشخص شده مطابقت دارند.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی برای مقایسه. علامت ستاره (*) مقدار ویژه‌ای است که با تمام برچسب‌ها مطابقت دارد. |
| namespaceURI | [String](../../../system/string/) | URI فضای‌نام برای مقایسه. |

### مقدار برگشتی

یک [XmlNodeList](../../xmlnodelist/) شامل فهرستی از تمام گره‌های مطابق. اگر گرهٔ مطابقی وجود نداشته باشد، فهرست خالی است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNodeList](../../xmlnodelist/)
* کلاس [String](../../../system/string/)
* کلاس [XmlElement](../)
* فضای نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)