---
title: Join()
second_title: Aspose.Slides برای مرجع API C++
description: آرایه را با استفاده از رشته به عنوان جداکننده ترکیب می‌کند.
type: docs
weight: 846
url: /fa/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) متد

آرایه را با استفاده از رشته به عنوان جداکننده ترکیب می‌کند.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) برای قرار دادن بین عناصر آرایه هنگام ترکیب آن‌ها. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) از قسمت‌ها برای ترکیب. |
| startIndex | int | اولین اندیس در آرایه برای شروع ترکیب. |
| count | int | تعداد عناصر آرایه برای ترکیب. -1 به معنی 'تا پایان آرایه'. |

### مقدار بازگشت

[String](../) که نمایانگر عناصر ترکیب‌شده آرایه است.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) متد

آرایه را با استفاده از رشته به عنوان جداکننده ترکیب می‌کند.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) برای قرار دادن بین عناصر آرایه هنگام ترکیب آن‌ها. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView از قسمت‌ها برای ترکیب. |
| startIndex | int | اولین اندیس در آرایه برای شروع ترکیب. |
| count | int | تعداد عناصر آرایه برای ترکیب. -1 به معنی 'تا پایان آرایه'. |

### مقدار بازگشت

[String](../) که نمایانگر عناصر ترکیب‌شده آرایه است.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) متد

آرایه را با استفاده از رشته به عنوان جداکننده ترکیب می‌کند.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) برای قرار دادن بین عناصر آرایه هنگام ترکیب آن‌ها. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - شیء قابل شمارش قسمت‌ها |

### مقدار بازگشت

[String](../) که نمایانگر عناصر ترکیب‌شده است.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) متد

آرایه را با استفاده از رشته به عنوان جداکننده ترکیب می‌کند.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) برای قرار دادن بین عناصر آرایه هنگام ترکیب آن‌ها. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) از قسمت‌ها برای ترکیب. |

### مقدار بازگشت

[String](../) که نمایانگر عناصر ترکیب‌شده است.

## موارد مرتبط

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* کلاس [Object](../../object/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)