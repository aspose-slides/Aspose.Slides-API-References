---
title: Console
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan metode untuk mengeluarkan data ke aliran output standar. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apapun.
type: docs
weight: 196
url: /id/system/console/
---
## Console kelas

Menyediakan metode untuk mengeluarkan data ke aliran output standar. Ini adalah tipe statik tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apapun.

```cpp
class Console
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static void [Beep](./beep/)() | BELUM DIIMPLEMENTASIKAN. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Mengembalikan shared pointer yang menunjuk ke objek yang mewakili aliran standar error. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Mengembalikan shared pointer yang menunjuk ke objek yang mewakili aliran standar input. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Mengembalikan shared pointer yang menunjuk ke objek yang mewakili aliran standar output. |
| static void [Mute](./mute/)(**bool**) | Membisukan atau membuka bisu aliran standar output. |
| static void [ReadKey](./readkey/)() | BELUM DIIMPLEMENTASIKAN. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Mengatur judul jendela konsol. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Menetapkan objek yang ditentukan ke properti Error kelas. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Mengatur properti In ke objek TextReader yang ditentukan. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Menetapkan objek yang ditentukan ke properti Out kelas. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Mengoutput representasi string dari objek yang ditentukan ke aliran standar output. |
| static void [Write](./write/)(**bool**) | Mengoutput representasi string dari nilai bool ke aliran standar output. |
| static void [Write](./write/)(char_t) | Mengoutput nilai karakter yang ditentukan ke aliran standar output. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Mengoutput representasi string dari array karakter yang ditentukan ke aliran standar output. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Mengoutput representasi string dari nilai [Decimal](../decimal/) ke aliran standar output. |
| static void [Write](./write/)(**double**) | Mengoutput representasi string dari nilai floating-point double-precision ke aliran standar output. |
| static void [Write](./write/)(**float**) | Mengoutput representasi string dari nilai floating-point single-precision ke aliran standar output. |
| static void [Write](./write/)(**int32_t**) | Mengoutput representasi string dari nilai integer 32-bit ke aliran standar output. |
| static void [Write](./write/)(**int64_t**) | Mengoutput representasi string dari nilai integer 64-bit ke aliran standar output. |
| static void [Write](./write/)(const [String](../string/)\&) | Mengoutput objek string yang ditentukan ke aliran standar output. |
| static void [Write](./write/)(const char_t *) | Mengoutput c-string yang ditentukan ke aliran standar output. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Mengoutput representasi string dari nilai [TypeInfo](../typeinfo/) ke aliran standar output. |
| static void [Write](./write/)(**uint32_t**) | Mengoutput representasi string dari nilai integer tak bertanda 32-bit ke aliran standar output. |
| static void [Write](./write/)(**uint64_t**) | Mengoutput representasi string dari nilai integer tak bertanda 64-bit ke aliran standar output. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Mengoutput representasi string dari rentang yang ditentukan dari array karakter yang ditentukan ke aliran standar output. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Mengoutput representasi string dari argumen yang ditentukan diformat sesuai format yang ditentukan ke aliran standar output. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Mengoutput penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Mengoutput representasi string dari objek yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(**bool**) | Mengoutput representasi string dari nilai bool diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(char_t) | Mengoutput nilai karakter yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Mengoutput representasi string dari array karakter yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Mengoutput representasi string dari nilai [Decimal](../decimal/) diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(**double**) | Mengoutput representasi string dari nilai floating-point double-precision diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(**float**) | Mengoutput representasi string dari nilai floating-point single-precision diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(**int32_t**) | Mengoutput representasi string dari nilai integer 32-bit diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(**int64_t**) | Mengoutput representasi string dari nilai integer 64-bit diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Mengoutput objek string yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const char_t *) | Mengoutput c-string yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Mengoutput representasi string dari nilai [TypeInfo](../typeinfo/) diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Mengoutput representasi string dari nilai integer tak bertanda 32-bit diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Mengoutput representasi string dari nilai integer tak bertanda 64-bit diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Mengoutput representasi string dari rentang yang ditentukan dari array karakter yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Mengoutput representasi string dari objek Exception yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Mengoutput representasi string dari argumen yang ditentukan diformat sesuai format yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran standar output. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Catatan

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Cetak pesan halo.
  Console::WriteLine(u"Hello, world!");

  // Buat instance dari kelas 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Cetak elemen-elemen array.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
Hello, world!
1 2 3 4 5
*/
```

## Lihat Juga

* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)