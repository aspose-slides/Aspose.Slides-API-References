---
title: EnumValues
second_title: مرجع API Aspose.Slides برای C++
description: اطلاعات متا دربارهٔ ثابت‌های شمارشی از نوع enum E را فراهم می‌کند.
type: docs
weight: 794
url: /fa/system/enumvalues/
---
## کلاس EnumValues

اطلاعات متا در مورد ثابت‌های شمارشی از نوع enum **E** را ارائه می‌دهد.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| E | نوع شمارش |
## متدها

| متد | توضیح |
| --- | --- |
|  [EnumValues](./enumvalues/)() | یک نمونه را می‌سازد. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | یک آرایه شامل همهٔ نام‌های شمارش **E** را برمی‌گرداند. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | یک آرایه از نام‌های ثابت‌های موجود در یک شمارش مشخص را بازیابی می‌کند. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | نوع زیرین شمارش مشخص شده را برمی‌گرداند. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | نوع زیرین شمارش مشخص شده را برمی‌گرداند. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | مقدار جعبه‌گذاری‌شدهٔ ثابت شمارش با نام مشخص شده را برمی‌گرداند. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | مقدار جعبه‌گذاری‌شدهٔ ثابت شمارش با مقدار مشخص شده را برمی‌گرداند. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | یک آرایه شامل همهٔ مقادیر شمارش **E** را برمی‌گرداند. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | یک آرایه شامل همهٔ مقادیر نوع شمارش مشخص شده را برمی‌گرداند. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | شیئی را برمی‌گرداند که مقدار ثابت شمارشی از نوع شمارش مشخص شده با نام مشخص‌شده را نمایان می‌کند. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | مقدار عدد صحیح ۶۴ بیتی بدون علامت مشخص شده را به یک عضو شمارش تبدیل می‌کند. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | شیء مشخص شده با مقدار عدد صحیح را به یک عضو شمارش تبدیل می‌کند. |
| virtual  [~EnumValues](./~enumvalues/)() | تخریب کننده. |

## همچنین ببینید

* کلاس [EnumValuesBase](../enumvaluesbase/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)