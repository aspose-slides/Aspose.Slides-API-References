---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan salinan slide master yang ditentukan ke posisi tertentu dalam koleksi. Slide tata letak yang terhubung juga akan disalin.
type: docs
weight: 105
url: /id/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metode

Menyisipkan salinan slide master yang ditentukan ke posisi tertentu dalam koleksi. Slide tata letak yang terhubung juga akan disalin.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) untuk digandakan. |

### Nilai Kembali

Slide master yang dimasukkan.
## Keterangan



Berikut contoh yang menunjukkan cara menggandakan slide master di PowerPoint [Presentation](../../presentation/) lain.
```cpp
// Membuat instance kelas Presentation untuk memuat file presentasi sumber
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Membuat instance kelas Presentation untuk presentasi tujuan (di mana slide akan digandakan)
auto destPres = System::MakeObject<Presentation>();

// Membuat instance ISlide dari koleksi slide dalam presentasi sumber bersama dengan
// Slide master
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Dapatkan Slide Master dari presentasi tujuan
auto masters = destPres->get_Masters();
// Gandakan slide master yang diinginkan dari presentasi sumber ke koleksi master dalam
// Presentasi tujuan
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Koleksi slide dalam presentasi tujuan
auto slides = destPres->get_Slides();
// Gandakan slide sumber ke koleksi slide tujuan.
slides->AddClone(sourceSlide, iSlide, true);
// Simpan presentasi tujuan ke disk
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [MasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)