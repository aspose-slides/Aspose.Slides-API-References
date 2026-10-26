---
title: ToObject()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار عدد صحیح بدون علامت 64 بیتی مشخص شده را به یک عضو شمارش تبدیل می‌کند.
type: docs
weight: 40
url: /fa/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) متد

مقدار عدد صحیح بدون علامت 64 بیتی مشخص شده را به یک عضو شمارش تبدیل می‌کند.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | نوع شمارشی که باید بازگرداند. |
| value | **uint64_t** | مقداری که باید به یک عضو شمارش تبدیل شود. |

### مقدار بازگشت

یک نمونه از شمارش که به مقدار داده شده تنظیم شده است.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) متد

شیء مشخص شده با مقدار عدد صحیح را به یک عضو شمارش تبدیل می‌کند.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | نوع شمارشی که باید بازگرداند. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | مقدار تبدیل‌شده به یک عضو شمارش. |

### مقدار بازگشت

یک شیء شمارشی که مقدار آن برابر با مقدار ورودی است.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [Object](../../object/)
* کلاس [TypeInfo](../../typeinfo/)
* کلاس [EnumValuesBase](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)