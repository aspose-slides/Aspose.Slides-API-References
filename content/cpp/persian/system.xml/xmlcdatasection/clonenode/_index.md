---
title: CloneNode()
second_title: مرجع API برای Aspose.Slides برای C++
description: یک نسخهٔ تکراری از این گره ایجاد می‌کند.
type: docs
weight: 53
url: /fa/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) متد


یک نسخهٔ تکراری از این گره ایجاد می‌کند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** برای کلون کردن بازگشتی زیر درخت زیر گرهٔ مشخص‌شده؛ **false** برای کلون کردن فقط خود گره. چون گره‌های CDATA فرزند ندارند، بدون توجه به تنظیم پارامتر، گرهٔ کلون‌شده همیشه شامل محتوای داده خواهد بود. |

### مقدار بازگشتی

گرهٔ کلون‌شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlCDataSection](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)