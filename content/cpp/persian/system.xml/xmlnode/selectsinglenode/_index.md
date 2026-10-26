---
title: SelectSingleNode()
second_title: مرجع API Aspose.Slides برای C++
description: اولین XmlNode که با عبارت XPath مطابقت دارد را انتخاب می‌کند.
type: docs
weight: 352
url: /fa/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) متد

اولین [XmlNode](../) را که با عبارت [XPath](../../../system.xml.xpath/) مطابقت دارد، انتخاب می‌کند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | عبارت [XPath](../../../system.xml.xpath/) |
 
### مقدار بازگشت

اولین [XmlNode](../) که با پرس و جوی [XPath](../../../system.xml.xpath/) مطابقت دارد یا **nullptr** اگر گره‌ای مطابق پیدا نشود.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) متد

اولین [XmlNode](../) را که با عبارت [XPath](../../../system.xml.xpath/) مطابقت دارد، انتخاب می‌کند. هر پیشوندی که در عبارت [XPath](../../../system.xml.xpath/) یافت شود با استفاده از [XmlNamespaceManager](../../xmlnamespacemanager/) ارائه شده حل می‌شود.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | عبارت [XPath](../../../system.xml.xpath/) |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | یک [XmlNamespaceManager](../../xmlnamespacemanager/) برای حل فضای نام برای پیشوندهای موجود در عبارت [XPath](../../../system.xml.xpath/) |
 
### مقدار بازگشت

اولین [XmlNode](../) که با پرس و جوی [XPath](../../../system.xml.xpath/) مطابقت دارد یا **nullptr** اگر گره‌ای مطابق پیدا نشود.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)