---
title: LookupNamespace()
second_title: مرجع API Aspose.Slides برای C++
description: URI فضای‌نام را برای پیشوند مشخص‌شده برمی‌گرداند.
type: docs
weight: 118
url: /fa/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) متد

URI فضای‌نام برای پیشوند مشخص‌شده را برمی‌گرداند.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | پیشوندی که می‌خواهید URI فضای‌نام آن را حل کنید. برای مطابقت با فضای‌نام پیش‌فرض، [String::Empty](../../../system/string/empty/) را بدهید. |

### مقدار بازگشتی

URI فضای‌نام برای **prefix** یا **nullptr** اگر فضای‌نامی مطابقت ندهد. رشته بازگردانده‌شده اتمی است. برای اطلاعات بیشتر درباره رشته‌های اتمی، به کلاس [XmlNameTable](../../xmlnametable/) مراجعه کنید.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlNamespaceManager](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)