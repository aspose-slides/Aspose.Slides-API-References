---
title: GetByte()
second_title: مرجع API Aspose.Slides برای C++
description: آرایهٔ تایپ‌شدهٔ مشخص‌شده را به عنوان یک آرایهٔ بایت خام تفسیر می‌کند و مقدار بایت را در انحراف بایتی تعیین‌شده بازیابی می‌کند.
type: docs
weight: 27
url: /fa/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) متد


آرایهٔ تایپ‌شدهٔ مشخص‌شده را به عنوان یک آرایهٔ بایت خام تفسیر می‌کند و مقدار بایت را در انحراف بایتی مشخص‌شده بازیابی می‌کند.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر آرایه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | آرایهٔ هدف |
| index | int | انحراف صفر-پایهٔ بایت برای بازیابی |

### مقدار بازگشت

مقدار بایت در ایندکس مشخص‌شده

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) متد


آرایهٔ تایپ‌شدهٔ مشخص‌شده را به عنوان یک آرایهٔ بایت خام تفسیر می‌کند و مقدار بایت را در انحراف بایتی مشخص‌شده بازیابی می‌کند.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر نمای آرایه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | نمای آرایهٔ هدف |
| index | int | انحراف صفر-پایهٔ بایت برای بازیابی |

### مقدار بازگشت

مقدار بایت در ایندکس مشخص‌شده

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) متد


آرایهٔ تایپ‌شدهٔ مشخص‌شده را به عنوان یک آرایهٔ بایت خام تفسیر می‌کند و مقدار بایت را در انحراف بایتی مشخص‌شده بازیابی می‌کند.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر آرایهٔ استک |
| N | اندازهٔ آرایهٔ استک |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | آرایهٔ استک هدف |
| index | int | انحراف صفر-پایهٔ بایت برای بازیابی |

### مقدار بازگشت

مقدار بایت در ایندکس مشخص‌شده

## موارد مرتبط

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)