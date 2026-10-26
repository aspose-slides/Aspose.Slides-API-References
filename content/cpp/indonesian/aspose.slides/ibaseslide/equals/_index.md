---
title: Equals()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah dua instance IBaseSlide sama. Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis. Dua slide dianggap sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll., sama. Perbandingan tidak memperhitungkan nilai pengenal unik, misalnya SlideId, dan konten dinamis, misalnya nilai tanggal saat ini dalam Date Placeholder.
type: docs
weight: 183
url: /id/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) metode

Menentukan apakah dua instance [IBaseSlide](../) sama. Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis. Dua slide dianggap sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll., sama. Perbandingan tidak memperhitungkan nilai pengenal unik, misalnya SlideId, dan konten dinamis, misalnya nilai tanggal saat ini dalam Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | [IBaseSlide](../) untuk dibandingkan dengan [IBaseSlide](../) saat ini. |

### Nilai Kembali

**true** jika [IBaseSlide](../) yang ditentukan sama dengan [IBaseSlide](../) saat ini; jika tidak, **false**.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IBaseSlide](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)