---
title: CloneNode()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نسخهٔ تکراری از این گره ایجاد می‌کند.
type: docs
weight: 40
url: /fa/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) متد

یک نسخهٔ تکراری از این گره ایجاد می‌کند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| deep | **bool** | **true** برای کپی‌گیری بازگشتی زیردرخت زیر گرهٔ مشخص شده؛ **false** برای کپی‌گیری فقط خود گره. از آنجا که گره‌های نظرات فرزندی ندارند، گرهٔ تکثیرشده همیشه شامل محتوای متن می‌شود، صرف‌نظر از تنظیم این پارامتر. |

### مقدار برگشتی

گرهٔ تکثیرشده.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlComment](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)