---
title: MakeRelativeUri()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan perbedaan antara URI yang direpresentasikan oleh objek saat ini dan objek Uri yang ditentukan.
type: docs
weight: 352
url: /id/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) metode


Menentukan perbedaan antara URI yang direpresentasikan oleh objek saat ini dan objek [Uri](../) yang ditentukan.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Komparan |

### Nilai Kembali

Jika nama host dan skema dari URI yang direpresentasikan oleh objek saat ini dan **toUri** sama, maka metode ini mengembalikan sebuah [Uri](../) relatif yang, ketika ditambahkan ke instance URI saat ini, menghasilkan **toUri**. Jika nama host atau skema berbeda, maka metode ini mengembalikan sebuah objek [Uri](../) yang merepresentasikan parameter **uri**.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Uri](../)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)