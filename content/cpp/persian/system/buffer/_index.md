---
title: Buffer
second_title: مرجع API Aspose.Slides برای C++
description: متدهایی را شامل می‌شود که آرایه‌های بایت خام را دستکاری می‌کنند. این یک نوع ایستاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وجه نمونه‌هایی از آن ایجاد کنید.
type: docs
weight: 144
url: /fa/system/buffer/
---
## کلاس Buffer

متدهایی را شامل می‌شود که آرایه‌های بایت خام را دستکاری می‌کنند. این یک نوع ایستاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وجه نمونه‌هایی از آن ایجاد کنید.

```cpp
class Buffer
```

## متدها

| متد | توضیح |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | تعداد مشخصی از بایت‌ها را از بافر منبع به بافر مقصد کپی می‌کند. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | دو آرایه تعریف‌شده مشخص را به عنوان آرایه‌های بایت خام تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | دو آرایه تعریف‌شده مشخص را به عنوان آرایه‌های بایت خام تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | دو آرایه تعریف‌شده مشخص را به عنوان آرایه‌های بایت خام تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | دو آرایه تعریف‌شده مشخص را به عنوان آرایه‌های بایت خام تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | دو آرایه تعریف‌شده مشخص را به عنوان آرایه‌های بایت خام تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | دو آرایه تعریف‌شده مشخص را به عنوان آرایه‌های بایت خام تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | دو آرایه تعریف‌شده مشخص را به عنوان آرایه‌های بایت خام تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | دو آرایه تعریف‌شده مشخص را به عنوان آرایه‌های بایت خام تفسیر می‌کند و داده‌ها را از یکی به دیگری کپی می‌کند. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | تعداد بایت‌های اشغال‌شده توسط تمام عناصر آرایه مشخص‌شده را تعیین می‌کند. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | تعداد بایت‌های اشغال‌شده توسط تمام عناصر آرایه مشخص‌شده را تعیین می‌کند. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | تعداد بایت‌های اشغال‌شده توسط تمام عناصر آرایه مشخص‌شده را تعیین می‌کند. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | آرایه تایپ‌شده مشخص را به عنوان آرایه بایت خام تفسیر می‌کند و مقدار بایت را در افست بایتی مشخص بازیابی می‌کند. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | آرایه تایپ‌شده مشخص را به عنوان آرایه بایت خام تفسیر می‌کند و مقدار بایت را در افست بایتی مشخص بازیابی می‌کند. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | آرایه تایپ‌شده مشخص را به عنوان آرایه بایت خام تفسیر می‌کند و مقدار بایت را در افست بایتی مشخص بازیابی می‌کند. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | آرایه تایپ‌شده مشخص را به عنوان آرایه بایت خام تفسیر می‌کند و مقدار بایت مشخص را در افست بایتی مشخص تنظیم می‌کند. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | آرایه تایپ‌شده مشخص را به عنوان آرایه بایت خام تفسیر می‌کند و مقدار بایت مشخص را در افست بایتی مشخص تنظیم می‌کند. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | آرایه تایپ‌شده مشخص را به عنوان آرایه بایت خام تفسیر می‌کند و مقدار بایت مشخص را در افست بایتی مشخص تنظیم می‌کند. |
## ملاحظات



```cpp
#include <system/buffer.h>

using namespace System;

void Print(const SmartPtr<Array<uint8_t>> &source, int size)
{
  for (auto i = 0; i < size; i++)
  {
    std::cout << static_cast<int>(source[i]) << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // آرایه را ایجاد و پر می‌کند.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // آیتم‌های آرایه را چاپ می‌کند.
  Print(first, SIZE);

  // آرایه‌ای ایجاد می‌کند که شامل بخشی از آرایه اول است.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // آیتم‌های آرایه دوم را چاپ می‌کند.
  Print(second, SIZE / 2);

  // مقدار آیتم در شاخص 0 را تنظیم می‌کند و آیتم‌های آرایه را چاپ می‌کند.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## مراجع مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)