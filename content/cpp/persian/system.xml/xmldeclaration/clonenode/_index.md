---
title: CloneNode()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخهٔ تکراری از این گره ایجاد می‌کند.
type: docs
weight: 157
url: /fa/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) متد

یک نسخهٔ تکراری از این گره را ایجاد می‌کند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| deep | **bool** | **true** برای کلون کردن بازگشت‌پذیر زیردرخت زیر گرهٔ مشخص‌شده؛ **false** برای کلون کردن فقط خود گره. چون گره‌های [XmlDeclaration](../) فرزند ندارند، گرهٔ کلون‌شده همیشه مقدار داده را شامل می‌شود، صرف‌نظر از تنظیم پارامتر. |

### مقدار برگشتی

گرهٔ کلون‌شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlDeclaration](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)