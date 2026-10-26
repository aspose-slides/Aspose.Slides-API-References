---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan salinan slide yang ditentukan ke akhir koleksi.
type: docs
weight: 14
url: /id/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) metode

Menambahkan salinan slide yang ditentukan ke akhir koleksi.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk diklon. |

### Nilai Kembali

Slide baru.

## Catatan

Ketika mengkloning sebuah slide antar presentasi yang berbeda, master slide dapat diklon juga. Registri internal digunakan untuk melacak master yang diklon secara otomatis agar mencegah pembuatan beberapa klon dari master slide yang sama. Kloning manual master slide tidak akan dicegah maupun didaftarkan. Jika Anda memerlukan kontrol lebih pada proses cloning, gunakan [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) atau [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) untuk mengkloning slide, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) atau [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) untuk mengkloning tata letak, dan [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) untuk mengkloning master.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metode

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk diklon. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) untuk slide baru. |

### Nilai Kembali

Slide baru.

## Catatan

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Sekarang bagian kedua berisi salinan slide pertama.
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metode

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk diklon. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout slide untuk slide baru. |

### Nilai Kembali

Slide baru.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metode

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk diklon. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide untuk slide baru. |
| allowCloneMissingLayout | **bool** | Jika tidak ada tata letak yang sesuai dalam master yang ditentukan, maka tata letak slide sumber akan diklon (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

### Nilai Kembali

Slide baru.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlide](../../islide/)
* Kelas [ISlideCollection](../)
* Kelas [ISection](../../isection/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)