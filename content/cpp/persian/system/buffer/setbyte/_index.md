---
title: SetByte()
second_title: مرجع API Aspose.Slides برای C++
description: آرایهٔ تایپ‌شدهٔ مشخص‌شده را به عنوان یک آرایه بایت خام درک می‌کند و مقدار بایت مشخص‌شده را در جابجایی بایت تعیین‌شده تنظیم می‌نماید.
type: docs
weight: 40
url: /fa/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) متد

آرایهٔ نوعی مشخص‌شده را به عنوان آرایه بایت خام درک می‌کند و مقدار بایت مشخص‌شده را در جابجایی بایت مشخص شده تنظیم می‌نماید.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر آرایه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | آرایه هدف |
| index | int | انحراف صفر-پایه بایت برای تنظیم |
| value | **uint8_t** | مقدار بایت برای تنظیم |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) متد

آرایهٔ نوعی مشخص‌شده را به عنوان آرایه بایت خام درک می‌کند و مقدار بایت مشخص‌شده را در جابجایی بایت مشخص شده تنظیم می‌نماید.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر آرایه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | نمای آرایه هدف |
| index | int | انحراف صفر-پایه بایت برای تنظیم |
| value | **uint8_t** | مقدار بایت برای تنظیم |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) متد

آرایهٔ نوعی مشخص‌شده را به عنوان آرایه بایت خام درک می‌کند و مقدار بایت مشخص‌شده را در جابجایی بایت مشخص شده تنظیم می‌نماید.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر آرایه |
| N | اندازهٔ آرایهٔ پشته |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | آرایه پشته هدف |
| index | int | انحراف صفر-پایه بایت برای تنظیم |
| value | **uint8_t** | مقدار بایت برای تنظیم |

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [Array](../../array/)
* کلاس [Buffer](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)