---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.
type: docs
weight: 66
url: /id/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) metode

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk diklon. |

### Nilai Kembalian

Slide yang disisipkan.

## Catatan

Ketika menyalin slide antara presentasi yang berbeda, master slide dapat diklon juga. Registri internal digunakan untuk melacak master yang diklon secara otomatis guna mencegah pembuatan banyak klon dari master slide yang sama. Kloning manual master slide tidak akan dicegah maupun didaftarkan. Jika Anda memerlukan kontrol lebih atas proses kloning, gunakan [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) atau [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) untuk mengkloning slide dan [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) untuk mengkloning master.

Contoh berikut menunjukkan cara mengklon pada posisi lain dalam [Presentation](../../presentation/).
```cpp
// Membuat instance kelas Presentation yang merepresentasikan file presentasi
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Mengklon slide yang diinginkan ke akhir koleksi slide dalam presentasi yang sama
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Mengklon slide yang diinginkan ke indeks yang ditentukan dalam presentasi yang sama
slides->InsertClone(2, slides->idx_get(1));
// Menulis presentasi yang telah dimodifikasi ke disk
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara mengklon pada posisi lain dalam [Presentation](../../presentation/). 
```cpp
// Membuat instance kelas Presentation untuk memuat file presentasi sumber
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Membuat instance kelas Presentation untuk PPTX tujuan (tempat slide akan diklon)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Menulis presentasi tujuan ke disk
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metode

Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk diklon. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Slide tata letak untuk slide baru. |

### Nilai Kembalian

Slide yang disisipkan.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metode

Menyisipkan salinan slide sumber yang ditentukan ke posisi yang ditentukan dalam koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai, maka tata letak slide sumber akan diklon (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk diklon. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide untuk slide baru. |
| allowCloneMissingLayout | **bool** | Jika tidak ada tata letak yang sesuai dalam master yang ditentukan, maka tata letak slide sumber akan diklon (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

### Nilai Kembalian

Slide yang disisipkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlide](../../islide/)
* Kelas [SlideCollection](../)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)