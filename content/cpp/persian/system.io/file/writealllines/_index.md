---
title: WriteAllLines()
second_title: مرجع API Aspose.Slides برای C++
description: یک فایل متنی جدید ایجاد می‌کند یا فایل موجود را بازنویسی می‌نماید و تمام رشته‌ها را از مجموعه قابل شمارش مشخص‌شده به آن می‌نویسد، به‌طوری که هر رشته در خط جدیدی قرار گیرد، با استفاده از رمزگذاری مشخص‌شده.
type: docs
weight: 456
url: /fa/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) متد

یک فایل متنی جدید می‌سازد یا فایل موجود را بازنویسی می‌کند و تمام رشته‌ها را از مجموعه قابل شمارش مشخص‌شده به آن می‌نویسد، به‌طوری که هر رشته در خط جدیدی قرار گیرد، با استفاده از رمزگذاری مشخص‌شده.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | فایلی که باید ایجاد یا بازنویسی شود |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | مجموعه‌ای قابل شمارش از رشته‌ها |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری کاراکتر مورد استفاده |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) متد

یک فایل متنی جدید می‌سازد یا فایل موجود را بازنویسی می‌کند و تمام رشته‌ها را از آرایهٔ مشخص‌شده به آن می‌نویسد، به‌طوری که هر رشته در خط جدیدی قرار گیرد، با استفاده از رمزگذاری مشخص‌شده.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | فایلی که باید ایجاد یا بازنویسی شود |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | آرایه‌ای از رشته‌ها |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری کاراکتر مورد استفاده |

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [EncodingPtr](../../../system/encodingptr/)
* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* کلاس [File](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)