---
title: AddNamespace()
second_title: Aspose.Slides برای C++ مرجع API
description: نام‌فضای داده‌شده را به مجموعه اضافه می‌کند.
type: docs
weight: 66
url: /fa/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) متد

نام‌فضای داده‌شده را به مجموعه اضافه می‌کند.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | پیش‌وندی که برای نام‌فضای اضافه‌شده مرتبط می‌شود. استفاده از [String::Empty](../../../system/string/empty/) برای افزودن یک نام‌فضای پیش‌فرض. اگر [XmlNamespaceManager](../) برای حل نام‌فضاها در یک عبارت XML Path Language ([XPath](../../../system.xml.xpath/)) استفاده شود، باید یک پیش‌وند مشخص گردد. اگر یک عبارت [XPath](../../../system.xml.xpath/) شامل پیش‌وند نباشد، فرض می‌شود که Uniform Resource Identifier (URI) یک نام‌فضای خالی است. برای اطلاعات بیشتر درباره عبارات [XPath](../../../system.xml.xpath/) و [XmlNamespaceManager](../)، به متدهای XmlNode::SelectNodes(String) و XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) مراجعه کنید. |
| uri | [String](../../../system/string/) | نام‌فضایی که باید اضافه شود. |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlNamespaceManager](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)