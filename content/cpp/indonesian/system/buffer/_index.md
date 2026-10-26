---
title: Buffer
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi metode yang memanipulasi array byte mentah. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh membuat instance darinya dengan cara apapun.
type: docs
weight: 144
url: /id/system/buffer/
---
## Buffer kelas


Berisi metode yang memanipulasi array byte mentah. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh membuat instance darinya dengan cara apapun.

```cpp
class Buffer
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Menyalin sejumlah byte yang ditentukan dari buffer sumber ke buffer tujuan. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Menginterpretasikan dua array bertipe yang ditentukan sebagai array byte mentah dan menyalin data dari salah satu ke yang lainnya. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Menginterpretasikan dua array yang ditentukan sebagai array byte mentah dan menyalin data dari salah satu ke yang lainnya. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Menginterpretasikan dua array bertipe yang ditentukan sebagai array byte mentah dan menyalin data dari salah satu ke yang lainnya. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Menginterpretasikan dua array bertipe yang ditentukan sebagai array byte mentah dan menyalin data dari salah satu ke yang lainnya. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Menginterpretasikan dua array bertipe yang ditentukan sebagai array byte mentah dan menyalin data dari salah satu ke yang lainnya. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Menginterpretasikan dua array bertipe yang ditentukan sebagai array byte mentah dan menyalin data dari salah satu ke yang lainnya. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Menginterpretasikan dua array bertipe yang ditentukan sebagai array byte mentah dan menyalin data dari salah satu ke yang lainnya. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Menginterpretasikan dua array bertipe yang ditentukan sebagai array byte mentah dan menyalin data dari salah satu ke yang lainnya. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Menentukan jumlah byte yang ditempati oleh semua elemen dari array yang ditentukan. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Menentukan jumlah byte yang ditempati oleh semua elemen dari array yang ditentukan. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Menentukan jumlah byte yang ditempati oleh semua elemen dari array yang ditentukan. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan mengambil nilai byte pada offset byte yang ditentukan. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan mengambil nilai byte pada offset byte yang ditentukan. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan mengambil nilai byte pada offset byte yang ditentukan. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan menetapkan nilai byte yang ditentukan pada offset byte yang ditentukan. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan menetapkan nilai byte yang ditentukan pada offset byte yang ditentukan. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Menginterpretasikan array bertipe yang ditentukan sebagai array byte mentah dan menetapkan nilai byte yang ditentukan pada offset byte yang ditentukan. |
## Catatan



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
  // Buat dan isi array.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Cetak elemen array.
  Print(first, SIZE);

  // Buat array yang berisi sebagian dari yang pertama.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Cetak elemen array kedua.
  Print(second, SIZE / 2);

  // Atur nilai elemen pada indeks 0 dan cetak elemen array.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Lihat Juga

* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)