---
title: Copy()
second_title: Aspose.Slides برای مرجع API C++
description: تعداد مشخصی از عناصر را از آرایه منبع به آرایه مقصد کپی می‌کند.
type: docs
weight: 729
url: /fa/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) متد

تعداد مشخصی از عناصر را از آرایه منبع به آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | آرایه منبع |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | آرایه مقصد |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) متد

تعداد مشخصی از عناصر را از نمای آرایه منبع به آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | نمای آرایه منبع |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | آرایه مقصد |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) متد

تعداد مشخصی از عناصر را از آرایه منبع به نمای آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | آرایه منبع |
| dstArray | System::Details::ArrayView\<DstType\> | نمای آرایه مقصد |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) متد

تعداد مشخصی از عناصر را از نمای آرایه منبع به نمای آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | نمای آرایه منبع |
| dstArray | System::Details::ArrayView\<DstType\> | نمای آرایه مقصد |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) متد

تعداد مشخصی از عناصر را از آرایه منبع روی پشته به آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | آرایه منبع روی پشته |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | آرایه مقصد |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) متد

تعداد مشخصی از عناصر را از آرایه منبع به آرایه مقصد روی پشته کپی می‌کند.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | آرایه منبع |
| dstArray | System::Details::StackArray\<DstType, N\>\& | آرایه مقصد روی پشته |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) متد

تعداد مشخصی از عناصر را از آرایه منبع روی پشته به آرایه مقصد روی پشته کپی می‌کند.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | آرایه منبع روی پشته |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | آرایه مقصد روی پشته |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) متد

تعداد معینی از عناصر را از آرایه منبع که از اندیس مشخص شروع می‌شود به موقعیت مشخص در آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| SrcType | نوع عناصر در آرایه منبع |
| DstType | نوع عناصر در آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | آرایه منبع |
| srcIndex | **int64_t** | [Index](../../index/) در آرایه منبع که آغاز بازهٔ موارد برای کپی را تعیین می‌کند |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | آرایه مقصد |
| dstIndex | **int64_t** | [Index](../../index/) در آرایه مقصد برای شروع وارد کردن موارد کپی شده |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) متد

تعداد معینی از عناصر را از نمای آرایه منبع که از اندیس مشخص شروع می‌شود به موقعیت مشخص در آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| SrcType | نوع عناصر در نمای آرایه منبع |
| DstType | نوع عناصر در آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | نمای آرایه منبع |
| srcIndex | **int64_t** | [Index](../../index/) در نمای آرایه منبع که آغاز بازهٔ موارد برای کپی را تعیین می‌کند |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | آرایه مقصد |
| dstIndex | **int64_t** | [Index](../../index/) در آرایه مقصد برای شروع وارد کردن موارد کپی شده |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) متد

تعداد معینی از عناصر را از آرایه منبع که از اندیس مشخص شروع می‌شود به موقعیت مشخص در نمای آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| SrcType | نوع عناصر در آرایه منبع |
| DstType | نوع عناصر در نمای آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | آرایه منبع |
| srcIndex | **int64_t** | [Index](../../index/) در آرایه منبع که آغاز بازهٔ موارد برای کپی را تعیین می‌کند |
| dstArray | System::Details::ArrayView\<DstType\> | نمای آرایه مقصد |
| dstIndex | **int64_t** | [Index](../../index/) در نمای آرایه مقصد برای شروع وارد کردن موارد کپی شده |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) متد

تعداد معینی از عناصر را از نمای آرایه منبع که از اندیس مشخص شروع می‌شود به موقعیت مشخص در نمای آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| SrcType | نوع عناصر در نمای آرایه منبع |
| DstType | نوع عناصر در نمای آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | نمای آرایه منبع |
| srcIndex | **int64_t** | [Index](../../index/) در نمای آرایه منبع که آغاز بازهٔ موارد برای کپی را تعیین می‌کند |
| dstArray | System::Details::ArrayView\<DstType\> | نمای آرایه مقصد |
| dstIndex | **int64_t** | [Index](../../index/) در نمای آرایه مقصد برای شروع وارد کردن موارد کپی شده |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) متد

تعداد معینی از عناصر را از آرایه منبع روی پشته که از اندیس مشخص شروع می‌شود به موقعیت مشخص در آرایه مقصد کپی می‌کند.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| SrcType | نوع عناصر در آرایه منبع روی پشته |
| DstType | نوع عناصر در آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | آرایه منبع روی پشته |
| srcIndex | **int64_t** | [Index](../../index/) در آرایه منبع روی پشته که آغاز بازهٔ موارد برای کپی را تعیین می‌کند |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | آرایه مقصد |
| dstIndex | **int64_t** | [Index](../../index/) در آرایه مقصد برای شروع وارد کردن موارد کپی شده |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) متد

تعداد معینی از عناصر را از آرایه منبع که از اندیس مشخص شروع می‌شود به موقعیت مشخص در آرایه مقصد روی پشته کپی می‌کند.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| SrcType | نوع عناصر در آرایه منبع |
| DstType | نوع عناصر در آرایه مقصد روی پشته |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | آرایه منبع |
| srcIndex | **int64_t** | [Index](../../index/) در آرایه منبع که آغاز بازهٔ موارد برای کپی را تعیین می‌کند |
| dstArray | System::Details::StackArray\<DstType, N\>\& | آرایه مقصد روی پشته |
| dstIndex | **int64_t** | [Index](../../index/) در آرایه مقصد روی پشته برای شروع وارد کردن موارد کپی شده |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) متد

تعداد معینی از عناصر را از آرایه منبع روی پشته که از اندیس مشخص شروع می‌شود به موقعیت مشخص در آرایه مقصد روی پشته کپی می‌کند.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| SrcType | نوع عناصر در آرایه منبع روی پشته |
| DstType | نوع عناصر در آرایه مقصد روی پشته |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | آرایه منبع روی پشته |
| srcIndex | **int64_t** | [Index](../../index/) در آرایه منبع روی پشته که آغاز بازهٔ موارد برای کپی را تعیین می‌کند |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | آرایه مقصد روی پشته |
| dstIndex | **int64_t** | [Index](../../index/) در آرایه مقصد روی پشته برای شروع وارد کردن موارد کپی شده |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) متد

تعداد معینی از عناصر را از نمای آرایه منبع که از اندیس مشخص شروع می‌شود به موقعیت مشخص در آرایه مقصد روی پشته کپی می‌کند.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| SrcType | نوع عناصر در آرایه منبع روی پشته |
| DstType | نوع عناصر در آرایه مقصد روی پشته |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | نمای آرایه منبع |
| srcIndex | **int64_t** | [Index](../../index/) در نمای آرایه منبع که آغاز بازهٔ موارد برای کپی را تعیین می‌کند |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | آرایه مقصد روی پشته |
| dstIndex | **int64_t** | [Index](../../index/) در آرایه مقصد روی پشته برای شروع وارد کردن موارد کپی شده |
| count | **int64_t** | تعداد عناصری که باید کپی شوند |

## See Also

* تعریف نوع [ArrayPtr](../../arrayptr/)
* کلاس [Array](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)