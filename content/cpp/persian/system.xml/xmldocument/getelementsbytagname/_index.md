---
title: GetElementsByTagName()
second_title: Aspose.Slides برای C++ API Reference
description: یک XmlNodeList را برمی‌گرداند که شامل فهرستی از تمام عناصر فرزند است که نام مشخص‌شده را مطابقت می‌دهند.
type: docs
weight: 443
url: /fa/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) متد


یک [XmlNodeList](../../xmlnodelist/) را برمی‌گرداند که شامل فهرستی از تمام عناصر فرزند است که نام مشخص‌شده را مطابقت می‌دهند.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name to match. It is matched against the **get_Name** value of the matching node. The special value **\"*\"** matches all tags. |

### مقدار بازگشتی

یک [XmlNodeList](../../xmlnodelist/) که شامل فهرستی از تمام گره‌های مطابق است. اگر هیچ گره‌ای با **name** مطابقت نداشته باشد، مجموعه‌ی بازگردانده شده خالی خواهد بود.

## XmlDocument::GetElementsByTagName(String, String) متد


یک [XmlNodeList](../../xmlnodelist/) را برمی‌گرداند که شامل فهرستی از تمام عناصر فرزند است که [XmlDocument::get_LocalName](../get_localname/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) مشخص‌شده را مطابقت می‌دهند.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | LocalName برای مطابقت. The special value **\"*\"** matches all tags. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI برای مطابقت. |

### مقدار بازگشتی

یک [XmlNodeList](../../xmlnodelist/) که شامل فهرستی از تمام گره‌های مطابقت است. اگر هیچ گره‌ای با **localName** و **namespaceURI** مطابقت نداشته باشد، مجموعه‌ی بازگردانده‌شده خالی خواهد بود.

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNodeList](../../xmlnodelist/)
* کلاس [String](../../../system/string/)
* کلاس [XmlDocument](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)