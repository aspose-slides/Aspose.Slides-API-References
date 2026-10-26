---
title: BlockCopy()
second_title: Aspose.Slides برای C++ مرجع API
description: تعداد مشخصی بایت را از بافر منبع به بافر مقصد کپی می‌کند.
type: docs
weight: 1
url: /fa/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) متد

تعداد مشخصی بایت را از بافر منبع به بافر مقصد کپی می‌کند.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const **uint8_t** * | اشاره‌گری به بافر منبع |
| srcOffset | int | یک افست بایت در بافر منبع که کپی از آن شروع می‌شود |
| dst | **uint8_t** * | اشاره‌گری به بافر مقصد |
| dstOffset | int | یک افست بایت در بافر مقصد که از آن شروع به وارد کردن داده می‌شود |
| count | int | تعداد بایت‌های قابل کپی |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) متد

دو آرایه تایپ‌شده مشخص را به‌عنوان آرایه‌های خام بایت تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TSrc | نوع عناصر آرایه منبع |
| TDst | نوع عناصر آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | آرایه منبع |
| srcOffset | int | یک افست بایت در آرایه منبع که کپی از آن شروع می‌شود |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | آرایه مقصد |
| dstOffset | int | یک افست بایت در آرایه مقصد که از آن شروع به وارد کردن داده می‌شود |
| count | int | تعداد بایت‌های قابل کپی |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) متد

دو آرایه مشخص را به‌عنوان آرایه‌های خام بایت تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | آرایه منبع |
| srcOffset | int | یک افست بایت در آرایه منبع که کپی از آن شروع می‌شود |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | آرایه مقصد |
| dstOffset | int | یک افست بایت در آرایه مقصد که از آن شروع به وارد کردن داده می‌شود |
| count | int | تعداد بایت‌های قابل کپی |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) متد

دو آرایه تایپ‌شده مشخص را به‌عنوان آرایه‌های خام بایت تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TSrc | نوع عناصر نمای آرایه منبع |
| TDst | نوع عناصر نمای آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | نمای آرایه منبع |
| srcOffset | int | یک افست بایت در نمای آرایه منبع که کپی از آن شروع می‌شود |
| dst | const System::Details::ArrayView\<TDst\>\& | نمای آرایه مقصد |
| dstOffset | int | یک افست بایت در نمای آرایه مقصد که از آن شروع به وارد کردن داده می‌شود |
| count | int | تعداد بایت‌های قابل کپی |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) متد

دو آرایه تایپ‌شده مشخص را به‌عنوان آرایه‌های خام بایت تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TSrc | نوع عناصر آرایه منبع |
| TDst | نوع عناصر نمای آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | آرایه منبع |
| srcOffset | int | یک افست بایت در آرایه منبع که کپی از آن شروع می‌شود |
| dst | const System::Details::ArrayView\<TDst\>\& | نمای آرایه مقصد |
| dstOffset | int | یک افست بایت در نمای آرایه مقصد که از آن شروع به وارد کردن داده می‌شود |
| count | int | تعداد بایت‌های قابل کپی |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) متد

دو آرایه تایپ‌شده مشخص را به‌عنوان آرایه‌های خام بایت تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TSrc | نوع عناصر نمای آرایه منبع |
| TDst | نوع عناصر آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | نمای آرایه منبع |
| srcOffset | int | یک افست بایت در نمای آرایه منبع که کپی از آن شروع می‌شود |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | آرایه مقصد |
| dstOffset | int | یک افست بایت در آرایه مقصد که از آن شروع به وارد کردن داده می‌شود |
| count | int | تعداد بایت‌های قابل کپی |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) متد

دو آرایه تایپ‌شده مشخص را به‌عنوان آرایه‌های خام بایت تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TSrc | نوع عناصر آرایه پشتهٔ منبع |
| NS | اندازهٔ آرایه پشتهٔ منبع |
| TDst | نوع عناصر آرایه پشتهٔ مقصد |
| ND | اندازهٔ آرایه پشتهٔ مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | آرایه پشتهٔ منبع |
| srcOffset | int | یک افست بایت در آرایه پشتهٔ منبع که کپی از آن شروع می‌شود |
| dst | const System::Details::StackArray\<TDst, ND\>\& | آرایه پشتهٔ مقصد |
| dstOffset | int | یک افست بایت در آرایه پشتهٔ مقصد که از آن شروع به وارد کردن داده می‌شود |
| count | int | تعداد بایت‌های قابل کپی |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) متد

دو آرایه تایپ‌شده مشخص را به‌عنوان آرایه‌های خام بایت تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TSrc | نوع عناصر آرایه منبع |
| TDst | نوع عناصر آرایه پشتهٔ مقصد |
| ND | اندازهٔ آرایه پشتهٔ مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | آرایه منبع |
| srcOffset | int | یک افست بایت در آرایه منبع که کپی از آن شروع می‌شود |
| dst | const System::Details::StackArray\<TDst, ND\>\& | آرایه پشتهٔ مقصد |
| dstOffset | int | یک افست بایت در آرایه پشتهٔ مقصد که از آن شروع به وارد کردن داده می‌شود |
| count | int | تعداد بایت‌های قابل کپی |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) متد

دو آرایه تایپ‌شده مشخص را به‌عنوان آرایه‌های خام بایت تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TSrc | نوع عناصر آرایه پشتهٔ منبع |
| NS | اندازهٔ آرایه پشتهٔ منبع |
| TDst | نوع عناصر آرایه مقصد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | آرایه پشتهٔ منبع |
| srcOffset | int | یک افست بایت در آرایه پشتهٔ منبع که کپی از آن شروع می‌شود |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | آرایه مقصد |
| dstOffset | int | یک افست بایت در آرایه مقصد که از آن شروع به وارد کردن داده می‌شود |
| count | int | تعداد بایت‌های قابل کپی |

## مراجع

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [Buffer](../)
* کلاس [Array](../../array/)
* کلاس [ArrayBase](../../arraybase/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)