---
title: ToArray()
second_title: Aspose.Slides برای مرجع API C++
description: یک آرایه شامل تمام فونت‌های FallBack برای این قانون ایجاد می‌کند و باز می‌گرداند.
type: docs
weight: 144
url: /fa/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() متد


یک آرایه شامل تمام فونت‌های FallBack برای این قانون ایجاد می‌کند و باز می‌گرداند.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```


### مقدار بازگشت

آرایه‌ای از [System::String](../../../system/string/)
## ملاحظات



```cpp
// یک قاعده ایجاد می‌کند که شامل فهرست فونت‌ها است.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// تمام نام‌های فونت را به‌صورت آرایه دریافت می‌کند.
ArrayPtr<String> fontNames = newRule->ToArray();
```


## FontFallBackRule::ToArray(int32_t, int32_t) متد


یک آرایه شامل تمام فونت‌های FallBack از بازهٔ مشخص شده در لیست ایجاد می‌کند و باز می‌گرداند.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | **int32_t** | نمایهٔ اولین فونتی که باید اضافه شود. |
| count | **int32_t** | تعداد فونت‌هایی که باید اضافه شوند. |

### مقدار بازگشت

آرایه‌ای از [System::String](../../../system/string/)
## ملاحظات



```cpp
// یک قاعده ایجاد می‌کند که شامل فهرست فونت‌ها است.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// دو نام آخرین فونت را به‌صورت آرایه دریافت می‌کند.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## مراجع

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [FontFallBackRule](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)