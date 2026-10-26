---
title: SelectNodes()
second_title: مرجع API Aspose.Slides برای C++
description: یک لیست از گره‌ها را که با عبارت XPath مطابقت دارند، انتخاب می‌کند.
type: docs
weight: 365
url: /fa/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method

یک لیست از گره‌ها را که با عبارت [XPath](../../../system.xml.xpath/) مطابقت دارند، انتخاب می‌کند.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | عبارت [XPath](../../../system.xml.xpath/). |

### مقدار بازگشت

یک [XmlNodeList](../../xmlnodelist/) که شامل مجموعه‌ای از گره‌ها است که با پرس‌وجوی [XPath](../../../system.xml.xpath/) مطابقت دارند.

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method

یک لیست از گره‌ها را که با عبارت [XPath](../../../system.xml.xpath/) مطابقت دارند، انتخاب می‌کند. هر پیشوندی که در عبارت [XPath](../../../system.xml.xpath/) یافت شود با استفاده از [XmlNamespaceManager](../../xmlnamespacemanager/) ارائه‌شده حل می‌شود.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | عبارت [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | یک [XmlNamespaceManager](../../xmlnamespacemanager/) برای استفاده در حل نام‌فضایی پیشوندها در عبارت [XPath](../../../system.xml.xpath/). |

### مقدار بازگشت

یک [XmlNodeList](../../xmlnodelist/) که شامل مجموعه‌ای از گره‌ها است که با پرس‌وجوی [XPath](../../../system.xml.xpath/) مطابقت دارند.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)