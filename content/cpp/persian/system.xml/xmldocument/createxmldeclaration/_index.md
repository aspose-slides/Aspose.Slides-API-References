---
title: CreateXmlDeclaration()
second_title: مرجع API Aspose.Slides برای C++
description: یک گره XmlDeclaration با مقادیر مشخص‌شده ایجاد می‌کند.
type: docs
weight: 378
url: /fa/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) متد

یک گرهٔ [XmlDeclaration](../../xmldeclaration/) را با مقادیر مشخص‌شده ایجاد می‌کند.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | نسخه باید \"1.0\" باشد. |
| encoding | const [String](../../../system/string/)\& | مقدار ویژگی encoding. این همان رمزگذاری است که هنگام ذخیرهٔ [XmlDocument](../) به یک فایل یا جریان استفاده می‌شود؛ بنابراین، باید به رشته‌ای که توسط کلاس [Text::Encoding](../../../system.text/encoding/) پشتیبانی می‌شود تنظیم شود، در غیر اینصورت \"XmlDocument::Save(String)\" شکست می‌خورد. اگر این مقدار **nullptr** یا [String::Empty](../../../system/string/empty/) باشد، متد [XmlDocument::Save](../save/) یک ویژگی encoding در اعلان XML نمی‌نویسد و بنابراین رمزگذاری پیش‌فرض، UTF-8، استفاده می‌شود. |
| standalone | const [String](../../../system/string/)\& | مقدار باید \"yes\" یا \"no\" باشد. اگر این مقدار **nullptr** یا [String::Empty](../../../system/string/empty/) باشد، متد [XmlDocument::Save](../save/) یک ویژگی standalone در اعلان XML نمی‌نویسد. |

### مقدار بازگشتی

گرهٔ جدید [XmlDeclaration](../../xmldeclaration/).

## توضیح

توجه: اگر [XmlDocument](../) به یک TextWriter یا [XmlTextWriter](../../xmltextwriter/) ذخیره شود، این مقدار رمزگذاری نادیده گرفته می‌شود. در عوض، رمزگذاری TextWriter یا [XmlTextWriter](../../xmltextwriter/) استفاده می‌شود. این تضمین می‌کند که XML خروجی با رمزگذاری صحیح قابل خواندن باشد.

## مراجعه کنید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlDeclaration](../../xmldeclaration/)
* کلاس [String](../../../system/string/)
* کلاس [XmlDocument](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)