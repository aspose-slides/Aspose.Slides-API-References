---
title: Buffer
second_title: Aspose.Slides for C++ API Referansı
description: Ham bayt dizilerini işleyen yöntemleri içerir. Bu, örnek hizmeti olmayan statik bir tiptir. Herhangi bir yolla ondan örnek oluşturulmamalıdır.
type: docs
weight: 144
url: /tr/system/buffer/
---
## Buffer sınıf


Ham bayt dizilerini işleyen yöntemleri içerir. Bu, örnek hizmeti olmayan statik bir tiptir. Herhangi bir yolla ondan örnek oluşturulmamalıdır.

```cpp
class Buffer
```

## Yöntemler

| Method | Description |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Belirtilen sayıda baytı kaynak tampondan hedef tamponuna kopyalar. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Belirtilen iki tipli diziyi ham bayt dizileri olarak yorumlar ve veriyi birinden diğerine kopyalar. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Belirtilen iki diziyi ham bayt dizileri olarak yorumlar ve veriyi birinden diğerine kopyalar. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Belirtilen iki tipli diziyi ham bayt dizileri olarak yorumlar ve veriyi birinden diğerine kopyalar. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Belirtilen iki tipli diziyi ham bayt dizileri olarak yorumlar ve veriyi birinden diğerine kopyalar. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Belirtilen iki tipli diziyi ham bayt dizileri olarak yorumlar ve veriyi birinden diğerine kopyalar. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Belirtilen iki tipli diziyi ham bayt dizileri olarak yorumlar ve veriyi birinden diğerine kopyalar. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Belirtilen iki tipli diziyi ham bayt dizileri olarak yorumlar ve veriyi birinden diğerine kopyalar. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Belirtilen iki tipli diziyi ham bayt dizileri olarak yorumlar ve veriyi birinden diğerine kopyalar. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Belirtilen dizinin tüm öğeleri tarafından kullanılan bayt sayısını belirler. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Belirtilen dizinin tüm öğeleri tarafından kullanılan bayt sayısını belirler. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Belirtilen dizinin tüm öğeleri tarafından kullanılan bayt sayısını belirler. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt kaydırımındaki bayt değerini alır. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt kaydırımındaki bayt değerini alır. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt kaydırımındaki bayt değerini alır. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt kaydırımındaki bayt değerini ayarlar. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt kaydırımındaki bayt değerini ayarlar. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt kaydırımındaki bayt değerini ayarlar. |
## Açıklamalar



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
  // Diziyi oluştur ve doldur.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Dizi öğelerini yazdır.
  Print(first, SIZE);

  // İlk dizinin bir bölümünü içeren bir dizi oluştur.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // İkinci dizinin öğelerini yazdır.
  Print(second, SIZE / 2);

  // 0. indeksteki öğenin değerini ayarla ve dizi öğelerini yazdır.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Ayrıca Bakınız

* AdAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)