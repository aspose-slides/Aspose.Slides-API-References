---
title: ToType()
second_title: Aspose.Slides برای C++ مرجع API
description: "مقدار این نمونه را به یک System::Object از System::Type مشخص‌شده که مقدار معادل دارد، با استفاده از اطلاعات قالب‌بندی خاص فرهنگ مشخص‌شده تبدیل می‌کند."
type: docs
weight: 209
url: /fa/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) متد


مقدار این نمونه را به یک [System::Object](../../object/) از System::Type مشخص شده که مقدار معادل دارد، با استفاده از اطلاعات قالب‌بندی خاص فرهنگ‌وار مشخص شده تبدیل می‌کند.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | System::Type که مقدار این نمونه به آن تبدیل می‌شود. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | یک پیاده‌سازی رابط [System::IFormatProvider](../../iformatprovider/) که اطلاعات قالب‌بندی خاص فرهنگ‌وار را فراهم می‌کند. |

### مقدار بازگشت

یک نمونه [System::Object](../../object/) از نوع conversionType که مقدار آن معادل مقدار این نمونه است.

## مراجع

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [Object](../../object/)
* کلاس [TypeInfo](../../typeinfo/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [IConvertible](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)