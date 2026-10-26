---
title: BufferedStream()
second_title: Aspose.Slides برای C++ API مرجع
description: یک شیء BufferedStream می‌سازد که جریانی که مشخص شده را می‌پیچند و از بافر 4096 بایتی استفاده می‌کند.
type: docs
weight: 1
url: /fa/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) سازنده

یک شیء [BufferedStream](../) را می‌سازد که جریانی که مشخص شده را می‌پیچند و از بافر 4096 بایتی استفاده می‌کند.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | شیء زیرین [Stream](../../stream/) |
 

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) سازنده

یک شیء [BufferedStream](../) می‌سازد که جریانی که مشخص شده را می‌پیچند و از بافری با اندازه مشخص شده استفاده می‌کند.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | شیء زیرین [Stream](../../stream/) |
| bufferSize | int | اندازهٔ بافر بر حسب بایت |

## مراجع مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Stream](../../stream/)
* کلاس [BufferedStream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)