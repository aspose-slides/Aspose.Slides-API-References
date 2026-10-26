---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.
type: docs
weight: 27
url: /id/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) metode

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk digandakan. |

### Nilai Kembali

Slide yang disisipkan.

## Catatan

Ketika menggandakan slide antara presentasi yang berbeda, master slide dapat digandakan juga. Registri internal digunakan untuk melacak master yang secara otomatis digandakan guna mencegah pembuatan beberapa klon dari master slide yang sama. Penggandaan manual master slide tidak akan dicegah maupun didaftarkan. Jika Anda membutuhkan kontrol lebih besar atas proses penggandaan, gunakan [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) atau [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) untuk menggandakan slide dan [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) untuk menggandakan master.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metode

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk digandakan. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Slide tata letak untuk slide baru. |

### Nilai Kembali

Slide yang disisipkan.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metode

Menyisipkan salinan slide sumber yang ditentukan ke posisi yang ditentukan dalam koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai, maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilemparkan (jika allowCloneMissingLayout bernilai false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk digandakan. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide master untuk slide baru. |
| allowCloneMissingLayout | **bool** | Jika tidak ada tata letak yang sesuai dalam master yang ditentukan, maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilemparkan (jika allowCloneMissingLayout bernilai false). |

### Nilai Kembali

Slide yang disisipkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlide](../../islide/)
* Kelas [ISlideCollection](../)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [IMasterSlide](../../imasterslide/)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)