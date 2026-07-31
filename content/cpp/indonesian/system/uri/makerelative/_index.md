---
title: MakeRelative()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan perbedaan antara dua instance Uri.
type: docs
weight: 365
url: /id/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) metode


Menentukan perbedaan antara dua [Uri](../) instance.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI yang dibandingkan dengan URI saat ini |

### Nilai Kembali

Jika hostname dan skema dari URI yang diwakili oleh objek saat ini dan **toUri** adalah sama, maka metode ini mengembalikan [String](../../string/) yang mewakili [Uri](../) relatif, ketika ditambahkan ke instance URI saat ini, menghasilkan **toUri**. Jika hostname atau skema berbeda, maka metode ini mengembalikan [String](../../string/) yang mewakili parameter **uri**.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [Uri](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)