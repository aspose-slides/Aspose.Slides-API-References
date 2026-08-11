---
title: Buffer
second_title: مرجع API Aspose.Slides للغة C++
description: يحتوي على طرق تتحكم في مصفوفات البايت الخام. هذا نوع ثابت دون خدمات مثيلات. لا يجب عليك أبدًا إنشاء مثيلات منه بأي وسيلة.
type: docs
weight: 144
url: /ar/system/buffer/
---
## Buffer فئة

يحتوي على طرق تتحكم في مصفوفات البايت الخام. هذا نوع ثابت دون خدمات مثيلات. لا يجب عليك أبدًا إنشاء مثيلات منه بأي وسيلة.

```cpp
class Buffer
```

## طرق

| Method | Description |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | ينسخ عددًا محددًا من البايتات من المخزن المؤقت المصدر إلى المخزن المؤقت الوجهة. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | يفسر مصفوفتين محددتين من نوع محدد كمصفوفات بايت خام وينسخ البيانات من إحداهما إلى الأخرى. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | يفسر مصفوفتين محددتين من نوع محدد كمصفوفات بايت خام وينسخ البيانات من إحداهما إلى الأخرى. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | يفسر مصفوفتين محددتين من نوع محدد كمصفوفات بايت خام وينسخ البيانات من إحداهما إلى الأخرى. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | يفسر مصفوفتين محددتين من نوع محدد كمصفوفات بايت خام وينسخ البيانات من إحداهما إلى الأخرى. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | يفسر مصفوفتين محددتين من نوع محدد كمصفوفات بايت خام وينسخ البيانات من إحداهما إلى الأخرى. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | يفسر مصفوفتين محددتين من نوع محدد كمصفوفات بايت خام وينسخ البيانات من إحداهما إلى الأخرى. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | يفسر مصفوفتين محددتين من نوع محدد كمصفوفات بايت خام وينسخ البيانات من إحداهما إلى الأخرى. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | يفسر مصفوفتين محددتين من نوع محدد كمصفوفات بايت خام وينسخ البيانات من إحداهما إلى الأخرى. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | يحدد عدد البايتات التي تشغلها جميع عناصر المصفوفة المحددة. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | يحدد عدد البايتات التي تشغلها جميع عناصر المصفوفة المحددة. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | يحدد عدد البايتات التي تشغلها جميع عناصر المصفوفة المحددة. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | يفسر المصفوفة المحددة من النوع المحدد كمصفوفة بايت خام ويسترجع قيمة البايت عند الإزاحة المحددة. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | يفسر المصفوفة المحددة من النوع المحدد كمصفوفة بايت خام ويسترجع قيمة البايت عند الإزاحة المحددة. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | يفسر المصفوفة المحددة من النوع المحدد كمصفوفة بايت خام ويسترجع قيمة البايت عند الإزاحة المحددة. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | يفسر المصفوفة المحددة من النوع المحدد كمصفوفة بايت خام ويضبط قيمة البايت المحددة عند الإزاحة المحددة. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | يفسر المصفوفة المحددة من النوع المحدد كمصفوفة بايت خام ويضبط قيمة البايت المحددة عند الإزاحة المحددة. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | يفسر المصفوفة المحددة من النوع المحدد كمصفوفة بايت خام ويضبط قيمة البايت المحددة عند الإزاحة المحددة. |
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
  // إنشاء وملء المصفوفة.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // طباعة عناصر المصفوفة.
  Print(first, SIZE);

  // إنشاء مصفوفة تحتوي على جزء من الأولى.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // طباعة عناصر المصفوفة الثانية.
  Print(second, SIZE / 2);

  // تعيين قيمة العنصر في الفهرس 0 وطباعة عناصر المصفوفة.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
مثال الشيفرة هذا ينتج المخرجات التالية:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## انظر أيضا

* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)