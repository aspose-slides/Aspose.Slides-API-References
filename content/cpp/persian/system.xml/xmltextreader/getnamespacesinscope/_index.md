---
title: GetNamespacesInScope()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای را بر می‌گرداند که شامل تمام فضای‌نام‌های هم‌اکنون در محدوده است.
type: docs
weight: 716
url: /fa/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) متد

برگرداندن یک مجموعه که شامل تمام فضای‌نام‌هایی است که هم‌اکنون در محدوده هستند.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | یک مقدار XmlNamespaceScope که نوع گره‌های فضای‌نامی را که باید بازگردانده شوند مشخص می‌کند. |

### مقدار بازگشتی

یک شیء IDictionary که تمام فضای‌نام‌های در-محدودهٔ جاری را شامل می‌شود. اگر خواننده روی عنصری قرار نگرفته باشد، یک دیکشنری خالی (بدون فضای‌نام) بازگردانده می‌شود.

## مراجع

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)