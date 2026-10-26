---
title: CloneNode()
second_title: مرجع API Aspose.Slides برای C++
description: یک کپی از این گره ایجاد می‌کند. گره‌های نوتیشن نمی‌توانند کلون شوند. فراخوانی این متد روی یک شیء XmlNotation یک استثنا پرتاب می‌کند.
type: docs
weight: 118
url: /fa/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) متد

یک کپی از این گره ایجاد می‌کند. گره‌های نوتیشن نمی‌توانند کلون شوند. فراخوانی این متد روی یک شیء [XmlNotation](../) یک استثنا پرتاب می‌کند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| deep | **bool** | **true** برای کلون کردن بازگشتی زیر درخت زیر گره مشخص شده؛ **false** برای کلون کردن فقط خود گره. |

### مقدار بازگشت

یک کپی [XmlNode](../../xmlnode/) از گره‌ای که متد از آن فراخوانی می‌شود.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlNotation](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)