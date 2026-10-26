---
title: idx_get()
second_title: مرجع API Aspose.Slides برای C++
description: "اولین عنصر فرزند را که با XmlNode::get_Name مشخص شده است، برمی‌گرداند."
type: docs
weight: 586
url: /fa/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) متد

اولین عنصر فرزند با [XmlNode::get_Name](../get_name/) مشخص شده را برمی‌گرداند.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام معتبر عنصری که باید بازیابی شود. |

### مقدار بازگشتی

اولین [XmlElement](../../xmlelement/) که با نام مشخص شده مطابقت دارد. اگر مطابقتی یافت نشود، **nullptr** برگردانده می‌شود.

## XmlNode::idx_get(String, String) متد

اولین عنصر فرزند با مقادیر [XmlNode::get_LocalName](../get_localname/) و [XmlNode::get_NamespaceURI](../get_namespaceuri/) مشخص شده را برمی‌گرداند.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localname | [String](../../../system/string/) | نام محلی عنصر. |
| ns | [String](../../../system/string/) | URI فضای نام عنصر. |

### مقدار بازگشتی

اولین [XmlElement](../../xmlelement/) که با **localname** و **ns** مطابقت دارد. اگر مطابقتی یافت نشود، **nullptr** برگردانده می‌شود.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlElement](../../xmlelement/)
* کلاس [String](../../../system/string/)
* کلاس [XmlNode](../)
* فضای نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)