---
title: Interlocked
second_title: Aspose.Slides untuk C++ Referensi API
description: Menyediakan API untuk operasi yang aman terhadap thread. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apapun.
type: docs
weight: 131
url: /id/system.threading/interlocked/
---
## Interlocked kelas

Menyediakan API untuk operasi yang aman terhadap thread. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apapun.

```cpp
class Interlocked
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Meningkatkan nilai secara atomik. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Meningkatkan nilai secara atomik. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Membandingkan dan menukar nilai pada variabel: memeriksa apakah variabel sama dengan nilai tertentu dan menyimpan nilai baru hanya jika nilai yang disimpan cocok dengan yang diharapkan. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Membandingkan dan menukar nilai pada variabel: memeriksa apakah variabel sama dengan nilai tertentu dan menyimpan nilai baru hanya jika nilai yang disimpan cocok dengan yang diharapkan. Tidak diimplementasikan. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Membandingkan dan menukar nilai pada variabel: memeriksa apakah variabel sama dengan nilai tertentu dan menyimpan nilai baru hanya jika nilai yang disimpan cocok dengan yang diharapkan. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Mengurangi nilai secara atomik. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Mengurangi nilai secara atomik. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Menukar nilai pada variabel: menyimpan nilai baru dan mengembalikan nilai yang dimiliki variabel tepat sebelum penyimpanan. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Menukar nilai pada variabel: menyimpan nilai baru dan mengembalikan nilai yang dimiliki variabel tepat sebelum penyimpanan. Tidak diimplementasikan. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Meningkatkan nilai secara atomik melalui prosedur exchange-add. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Meningkatkan nilai secara atomik melalui prosedur exchange-add. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Meningkatkan nilai secara atomik. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Meningkatkan nilai secara atomik. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Mengembalikan nilai 64-bit, dimuat sebagai operasi atomik. |

## Lihat Juga

* Ruang Nama [System::Threading](../)
* Perpustakaan [Aspose.Slides](../../)