---
title: IOControl()
second_title: مرجع API Aspose.Slides برای C++
description: حالت‌های عملیاتی سطح پایین را برای سوکت تنظیم می‌کند.
type: docs
weight: 703
url: /fa/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

حالت‌های عملیاتی سطح پایین را برای سوکت تنظیم می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ioControlCode | **int32_t** | کد کنترل عملیاتی که باید اجرا شود. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که شامل داده‌های ورودی است. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که شامل داده‌های خروجی است. |

### مقدار بازگشت

تعداد بایت‌ها در پارامتر **optionOutValue** است.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

حالت‌های عملیاتی سطح پایین را برای سوکت تنظیم می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | کد کنترل عملیاتی که باید اجرا شود. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که شامل داده‌های ورودی است. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که شامل داده‌های خروجی است. |

### مقدار بازگشت

تعداد بایت‌ها در پارامتر **optionOutValue** است.

## موارد مرتبط

* enum [IOControlCode](../../iocontrolcode/)
* typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [Socket](../)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)