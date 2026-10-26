---
title: Equals()
second_title: Aspose.Slides برای C++ مرجع API
description: اشیاء را با استفاده از معانی Object.Equals در C# مقایسه می‌کند.
type: docs
weight: 157
url: /fa/system/object/equals/
---
## Object::Equals(ptr) متد

اشیاء را با استفاده از معنای [Object.Equals](./) در C# مقایسه می‌کند.

```cpp
virtual bool System::Object::Equals(ptr obj)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) برای مقایسه‌ی شیء فعلی. |

### مقدار بازگشت

اگر اشیاء برابر در نظر گرفته شوند True و در غیر این صورت false.

## Object::Equals(T1 const\&, T2 const\&) متد

اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع اولین شیء برای مقایسه. |
| T2 | نوع دومین شیء برای مقایسه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| objA | T1 const\& | اولین شیء برای مقایسه. |
| objB | T2 const\& | دومین شیء برای مقایسه. |

### مقدار بازگشت

اگر اشیاء یا از طریق ارجاع یا به صورت معنایی (با مقایسه‌ای شبیه [Object.Equals](./)) مطابقت داشته باشند True و در غیر این صورت false.

## Object::Equals(T1 const\&, T2 const\&) متد

اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع اولین شیء برای مقایسه. |
| T2 | نوع دومین شیء برای مقایسه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| objA | T1 const\& | اولین شیء برای مقایسه. |
| objB | T2 const\& | دومین شیء برای مقایسه. |

### مقدار بازگشت

اگر اشیاء با استفاده از عملگر مساوی‌سازی موجود برابر در نظر گرفته شوند True و در غیر این صورت false.

## Object::Equals(float const\&, float const\&) متد

مقایسه‌ی نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989، NaN برابر با هیچ مقداری، از جمله NaN، نیست.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| objA | **float** const\& | مقدار نقطه شناور سمت چپ. |
| objB | **float** const\& | مقدار نقطه شناور سمت راست. |

### مقدار بازگشت

اگر **objA** و **objB** هر دو NaN یا برابر باشند True و در غیر این صورت false.

## Object::Equals(double const\&, double const\&) متد

مقایسه‌ی نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989، NaN برابر با هیچ مقداری، از جمله NaN، نیست.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| objA | **double** const\& | مقدار نقطه شناور سمت چپ. |
| objB | **double** const\& | مقدار نقطه شناور سمت راست. |

### مقدار بازگشت

اگر **objA** و **objB** هر دو NaN یا برابر باشند True و در غیر این صورت false.

## موارد مرتبط

* تعریف نوع [ptr](../ptr/)
* کلاس [Object](../)
* ساختار [IsSmartPtr](../../issmartptr/)
* نام‌فضا [System](../../)
* کتابخانه [Aspose.Slides](../../../)