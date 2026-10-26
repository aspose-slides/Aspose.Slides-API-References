---
title: ByteLength()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که چه تعداد بایت توسط تمام عناصر آرایهٔ مشخص‌شده اشغال می‌شود.
type: docs
weight: 14
url: /fa/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) متد


تعیین می‌کند که چه تعداد بایت توسط تمام عناصر آرایهٔ مشخص‌شده اشغال می‌شود.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | An array |

### مقدار بازگشتی

The number of bytes occupied by all elements of the specified array

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) متد


تعیین می‌کند که چه تعداد بایت توسط تمام عناصر آرایهٔ مشخص‌شده اشغال می‌شود.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array view |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | An array view |

### مقدار بازگشتی

The number of bytes occupied by all elements of the specified array view

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) متد


تعیین می‌کند که چه تعداد بایت توسط تمام عناصر آرایهٔ مشخص‌شده اشغال می‌شود.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | An stack array |

### مقدار بازگشتی

The number of bytes occupied by all elements of the specified stack array

## موارد مرتبط

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [Array](../../array/)
* کلاس [Buffer](../)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)