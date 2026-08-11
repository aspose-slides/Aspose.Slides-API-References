---
title: AppendAllLines()
second_title: Aspose.Slides برای مرجع API C++
description: رشته‌ها را از مجموعهٔ مشخص شدهٔ رشته‌ها به فایل مشخص‌شده اضافه می‌کند با استفاده از رمزگذاری مشخص شده و با نوشتن هر رشته در یک خط جدید. اگر فایل مشخص‌شده وجود نداشته باشد، ایجاد می‌شود. پس از نوشتن تمام رشته‌ها، فایل بسته می‌شود.
type: docs
weight: 1
url: /fa/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) متد

رشته‌ها را از مجموعهٔ مشخص شدهٔ رشته‌ها به فایل مشخص‌شده اضافه می‌کند با استفاده از رمزگذاری مشخص‌شده، به طوری که هر رشته در یک خط جدید نوشته می‌شود. اگر فایل مشخص‌شده وجود نداشته باشد، ایجاد می‌شود. پس از نوشتن تمام رشته‌ها، فایل بسته می‌شود.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایلی که رشته‌ها به آن اضافه می‌شود |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | رشته‌هایی که در فایل نوشته می‌شوند |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری کاراکتری که استفاده می‌شود |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* کلاس [String](../../../system/string/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* کلاس [File](../)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)