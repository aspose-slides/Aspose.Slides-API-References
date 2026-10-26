---
title: Parse()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار ثابت شمارشی از شمارش‌گر مشخص‌شده با نام معین را به‌صورت جعبه‌بندی می‌کند. یک پارامتر تعیین می‌کند که هنگام تفسیر رشته‌ای که نام ثابت شمارشی را مشخص می‌کند، حساسیت به حروف بزرگ و کوچک نادیده گرفته شود.
type: docs
weight: 53
url: /fa/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) متد

مقدار ثابت شمارشی از شمارش‌گر مشخص‌شده با نام معین را به‌صورت جعبه‌بندی می‌کند. یک پارامتر تعیین می‌کند که هنگام تفسیر رشته‌ای که نام ثابت شمارشی را مشخص می‌کند، حساسیت به حروف بزرگ و کوچک نادیده گرفته شود.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | نوع شمارش‌گر را مشخص می‌کند |
| str | const [String](../../string/)\& | نام ثابت شمارشی که مقدار آن جعبه‌بندی می‌شود |
| ignoreCase | **bool** | تعیین می‌کند که هنگام تفسیر رشته‌ی نمایانگر نام ثابت شمارشی، حساسیت به حروف بزرگ و کوچک نادیده گرفته شود |

### مقدار بازگشت

یک shared pointer به شیئی که مقدار جعبه‌بندی‌شده‌ی ثابت شمارشی مشخص‌شده را نمایان می‌کند

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) متد

مقدار ثابت شمارشی از شمارش‌گر مشخص‌شده با نام معین را به‌صورت جعبه‌بندی می‌کند.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | نوع شمارش‌گر را مشخص می‌کند |
| str | const [String](../../string/)\& | نام ثابت شمارشی که مقدار آن جعبه‌بندی می‌شود |

### مقدار بازگشت

یک shared pointer به شیئی که مقدار جعبه‌بندی‌شده‌ی ثابت شمارشی مشخص‌شده را نمایان می‌کند

## موارد مرتبط

* تعریف نوع [SharedPtr](../../sharedptr/)
* کلاس [Object](../../object/)
* کلاس [TypeInfo](../../typeinfo/)
* کلاس [String](../../string/)
* کلاس [BoxedValueBase](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)