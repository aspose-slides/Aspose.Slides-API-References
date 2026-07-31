---
title: Handle()
second_title: Aspose.Slides untuk C++ Referensi API
description: Memanggil fungsi penangan pada setiap exception dalam dan melempar kembali setiap exception yang tidak ditangani.
type: docs
weight: 66
url: /id/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) metode

Memanggil fungsi penangan pada setiap exception dalam dan melempar kembali setiap exception yang tidak ditangani.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Fungsi yang menerima sebuah Exception dan mengembalikan true bila ditangani. |
## Catatan

Jika semua exception ditangani, metode ini mengembalikan secara normal; jika tidak, sebuah AggregateException baru yang berisi exception yang tidak ditangani akan dilemparkan. 

## Lihat Juga

* Typedef [Exception](../../exception/)
* Kelas [Func](../../func/)
* Kelas [Details_AggregateException](../)
* RuangNama [System](../../)
* Library [Aspose.Slides](../../../)