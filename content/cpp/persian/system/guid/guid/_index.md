---
title: Guid()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء را می‌سازد که GUID‌ای را نشان می‌دهد که از تمام صفرها تشکیل شده است.
type: docs
weight: 1
url: /fa/system/guid/guid/
---
## Guid::Guid() سازنده

یک شیء را می‌سازد که GUID‌ای را نشان می‌دهد که از تمام صفرها تشکیل شده است.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) سازنده

یک شیء را می‌سازد که GUID را که به صورت آرایه‌ای از مقادیر صحیح ۸ بیتی بدون علامت مشخص شده است، نشان می‌دهد.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | یک آرایه بایت حاوی بایت‌های جداگانهٔ GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) سازنده

یک شیء را می‌سازد که GUID را که به صورت نمای آرایه‌ای از مقادیر صحیح ۸ بیتی بدون علامت مشخص شده است، نشان می‌دهد.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | یک آرایه بایت حاوی بایت‌های جداگانهٔ GUID |

## Guid::Guid(const String\&) سازنده

یک شیء را می‌سازد که GUID را که به صورت رشته‌ای مشخص شده است، نشان می‌دهد.

```cpp
System::Guid::Guid(const String &g)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| g | const [String](../../string/)\& | نمایش رشته‌ای یک GUID که توسط شیء ساخته شده نمایان می‌شود |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) سازنده

یک نمونه از کلاس [Guid](../) را از مؤلفه‌های مشخص شدهٔ GUID می‌سازد.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | **int32_t** | بیت‌های ۰-۳۱ GUID |
| b | **int16_t** | بیت‌های ۳۲-۴۷ GUID |
| c | **int16_t** | بیت‌های ۴۸-۶۳ GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | یک آرایه بایت حاوی بیت‌های ۶۴-۱۲۷ GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) سازنده

یک نمونه از کلاس [Guid](../) را از مؤلفه‌های مشخص شدهٔ GUID می‌سازد.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | **int32_t** | بیت‌های ۰-۳۱ GUID |
| b | **int16_t** | بیت‌های ۳۲-۴۷ GUID |
| c | **int16_t** | بیت‌های ۴۸-۶۳ GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه بایت حاوی بیت‌های ۶۴-۱۲۷ GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) سازنده

یک نمونه از کلاس [Guid](../) را از اعداد صحیح بدون علامت و بایت‌های مشخص شده می‌سازد.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | **int32_t** | بیت‌های ۰-۳۱ GUID |
| b | **int16_t** | بیت‌های ۳۲-۴۷ GUID |
| c | **int16_t** | بیت‌های ۴۸-۶۳ GUID |
| d | **uint8_t** | بیت‌های ۶۴-۷۱ GUID |
| e | **uint8_t** | بیت‌های ۷۲-۷۹ GUID |
| f | **uint8_t** | بیت‌های ۸۰-۸۷ GUID |
| g | **uint8_t** | بیت‌های ۸۸-۹۵ GUID |
| h | **uint8_t** | بیت‌های ۹۶-۱۰۳ GUID |
| i | **uint8_t** | بیت‌های ۱۰۴-۱۱۱ GUID |
| j | **uint8_t** | بیت‌های ۱۱۲-۱۱۹ GUID |
| k | **uint8_t** | بیت‌های ۱۲۰-۱۲۷ GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) سازنده

یک نمونه از کلاس [Guid](../) را از اعداد صحیح بدون علامت و بایت‌های مشخص شده می‌سازد.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | **uint32_t** | بیت‌های ۰-۳۱ GUID |
| b | **uint16_t** | بیت‌های ۳۲-۴۷ GUID |
| c | **uint16_t** | بیت‌های ۴۸-۶۳ GUID |
| d | **uint8_t** | بیت‌های ۶۴-۷۱ GUID |
| e | **uint8_t** | بیت‌های ۷۲-۷۹ GUID |
| f | **uint8_t** | بیت‌های ۸۰-۸۷ GUID |
| g | **uint8_t** | بیت‌های ۸۸-۹۵ GUID |
| h | **uint8_t** | بیت‌های ۹۶-۱۰۳ GUID |
| i | **uint8_t** | بیت‌های ۱۰۴-۱۱۱ GUID |
| j | **uint8_t** | بیت‌های ۱۱۲-۱۱۹ GUID |
| k | **uint8_t** | بیت‌های ۱۲۰-۱۲۷ GUID |

## Guid::Guid(const Guid\&) سازنده

یک شیء را می‌سازد که همان GUID را که توسط شیء مشخص شده است، نشان می‌دهد.

```cpp
System::Guid::Guid(const Guid &guid)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| guid | const [Guid](../)\& | شیء [Guid](../) برای کپی مقدار GUID از آن |

## مراجع

* تعریف نوع [ArrayPtr](../../arrayptr/)
* کلاس [Guid](../)
* کلاس [String](../../string/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)