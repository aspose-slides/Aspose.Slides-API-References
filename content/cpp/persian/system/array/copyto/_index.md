---
title: CopyTo()
second_title: مرجع API Aspose.Slides برای C++
description: تمام عناصر آرایهٔ جاری را به آرایه مقصد مشخص‌شده کپی می‌کند. عناصر در آرایه مقصد از اندیسی که توسط آرگومان arrayIndex مشخص شده شروع به قرارگیری می‌شوند.
type: docs
weight: 118
url: /fa/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) متد

تمام عناصر آرایهٔ جاری را به آرایه مقصد مشخص‌شده کپی می‌کند. عناصر در آرایهٔ مقصد از اندیسی که توسط آرگومان arrayIndex مشخص شده شروع به قرارگیری می‌شوند.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | آرایه مقصد |
| arrayIndex | int | [Index](../../index/) در آرایه مقصد برای شروع وارد کردن آیتم‌های کپی‌شده |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const متد

تمام عناصر آرایهٔ جاری را به آرایه مقصد مشخص‌شده کپی می‌کند. عناصر در آرایهٔ مقصد از اندیسی که توسط آرگومان dstIndex مشخص شده شروع به قرارگیری می‌شوند.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| DstType | نوع عناصر در آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | آرایه مقصد |
| dstIndex | **int64_t** | [Index](../../index/) در آرایه مقصد برای شروع وارد کردن آیتم‌های کپی‌شده |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const متد

تمام عناصر آرایهٔ جاری را به نمای آرایه مقصد مشخص‌شده کپی می‌کند. عناصر در نمای آرایهٔ مقصد از اندیسی که توسط آرگومان dstIndex مشخص شده شروع به قرارگیری می‌شوند.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| DstType | نوع عناصر در نمای آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | نمای آرایه مقصد |
| dstIndex | **int64_t** | [Index](../../index/) در نمای آرایه مقصد برای شروع وارد کردن آیتم‌های کپی‌شده |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const متد

تعدادی مشخص از عناصر را از آرایهٔ جاری که از موقعیت مشخص‌شده شروع می‌شود، به آرایه مقصد مشخص‌شده کپی می‌کند. عناصر در آرایهٔ مقصد از اندیسی که توسط آرگومان dstIndex مشخص شده شروع به قرارگیری می‌شوند.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| DstType | نوع عناصر در آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | آرایه مقصد |
| srcIndex | **int64_t** | [Index](../../index/) در آرایه منبع برای شروع کپی آیتم‌ها |
| dstIndex | **int64_t** | [Index](../../index/) در آرایه مقصد برای شروع وارد کردن آیتم‌های کپی‌شده |
| count | **int64_t** | تعداد عناصر برای کپی |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const متد

تعدادی مشخص از عناصر را از آرایهٔ جاری که از موقعیت مشخص‌شده شروع می‌شود، به نمای آرایه مقصد مشخص‌شده کپی می‌کند. عناصر در نمای آرایهٔ مقصد از اندیسی که توسط آرگومان dstIndex مشخص شده شروع به قرارگیری می‌شوند.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| DstType | نوع عناصر در نمای آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | نمای آرایه مقصد |
| srcIndex | **int64_t** | [Index](../../index/) در آرایه منبع برای شروع کپی آیتم‌ها |
| dstIndex | **int64_t** | [Index](../../index/) در نمای آرایه مقصد برای شروع وارد کردن آیتم‌های کپی‌شده |
| count | **int64_t** | تعداد عناصر برای کپی |

## مراجع

* تعریف نوع [ArrayPtr](../../arrayptr/)
* کلاس [Array](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)