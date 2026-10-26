---
title: Semaphore()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ semaphore غير مسمى.
type: docs
weight: 1
url: /ar/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) منشئ

Creates unnamed semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| initialCount | int | العدد الأولي للمدخلات النشطة. |
| maximumCount | int | العدد الأقصى المسموح به للمدخلات. |

## Semaphore::Semaphore(int, int, const String\&) منشئ

Creates named semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| initialCount | int | العدد الأولي للمدخلات النشطة. |
| maximumCount | int | العدد الأقصى المسموح به للمدخلات. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) الاسم. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) منشئ

Creates named semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| initialCount | int | العدد الأولي للمدخلات النشطة. |
| maximumCount | int | العدد الأقصى المسموح به للمدخلات. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) الاسم. |
| createdNew | **bool**\& | مرجع إلى المتغيّر الذي يُعيَّن إلى true إذا تم إنشاء الـ semaphore وإلى false إذا تم إعادة استخدام واحد موجود بالاسم نفسه |

## انظر أيضا

* الفئة [Semaphore](../)
* الفئة [String](../../../system/string/)
* النطاق [System::Threading](../../)
* المكتبة [Aspose.Slides](../../../)