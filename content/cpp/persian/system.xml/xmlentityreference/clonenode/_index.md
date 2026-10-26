---
title: CloneNode()
second_title: Aspose.Slides برای مرجع API C++
description: یک نسخهٔ تکراری از این گره را ایجاد می‌کند.
type: docs
weight: 92
url: /fa/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) متد

یک نسخهٔ تکراری از این گره را ایجاد می‌کند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| deep | **bool** | **true** برای کلون کردن بازگشت‌پذیر زیرشاخه زیر گرهٔ مشخص‌شده؛ **false** برای کلون کردن فقط خود گره. برای گره‌های [XmlEntityReference](../)، این متد همیشه یک گرهٔ ارجاع موجودیت بدون فرزند برمی‌گرداند. متن جایگزین زمانی تنظیم می‌شود که گره به یک والد وارد شود. |

### مقدار بازگشت

گرهٔ کلون‌شده.

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlEntityReference](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)