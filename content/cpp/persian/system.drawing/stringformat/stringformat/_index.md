---
title: StringFormat()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس StringFormat را می‌سازد.
type: docs
weight: 1
url: /fa/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() سازنده

یک نمونه جدید از کلاس [StringFormat](../) می‌سازد.

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) سازنده

یک نمونه جدید از کلاس [StringFormat](../) را با پرچم‌های قالب مشخص‌شده و زبان ایجاد می‌کند.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | ترکیبی بیتی از مقادیر شمارش StringFormatFlags که قالب رشته‌ای را که شیء ایجاد شونده باید نمایانگرش باشد، تعیین می‌کند |
| language | **int32_t** | زبانی که متن به آن تعلق دارد |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) سازنده

سازندهٔ کپی.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | یک شیء [StringFormat](../) برای کپی |

## موارد مرتبط

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [StringFormat](../)
* فضای‌نام [System::Drawing](../../)
* Library [Aspose.Slides](../../../)