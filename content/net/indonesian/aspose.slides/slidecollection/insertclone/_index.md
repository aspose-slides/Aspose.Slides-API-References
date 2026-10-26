---
title: InsertClone
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menyisipkan salinan slide yang ditentukan ke posisi tertentu dalam koleksi.
type: docs
weight: 120
url: /id/aspose.slides/slidecollection/insertclone/
---
## InsertClone(int, ISlide) {#insertclone}

Menyisipkan salinan slide yang ditentukan ke posisi tertentu dalam koleksi.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Indeks slide baru. |
| sourceSlide | ISlide | Slide yang akan digandakan. |

### Nilai Kembalian

Slide yang disisipkan.

### Catatan

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use [`InsertClone`](../insertclone) or [`InsertClone`](../insertclone) for cloning slides and [`AddClone`](../../imasterslidecollection/addclone) for cloning masters.

### Contoh

Contoh berikut menunjukkan cara menggandakan pada posisi lain dalam Presentation.

```csharp
[C#]
// Instansiasi kelas Presentation yang mewakili file presentasi
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Gandakan slide yang diinginkan ke akhir koleksi slide dalam presentasi yang sama
    ISlideCollection slds = pres.Slides;
    // Gandakan slide yang diinginkan ke indeks yang ditentukan dalam presentasi yang sama
    slds.InsertClone(2, pres.Slides[1]);
    // Tuliskan presentasi yang telah dimodifikasi ke disk
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

Contoh berikut menunjukkan cara menggandakan pada posisi lain dalam Presentation.

```csharp
[C#]
// Instansiasi kelas Presentation untuk memuat file presentasi sumber
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Instansiasi kelas Presentation untuk PPTX tujuan (di mana slide akan digandakan)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Tuliskan presentasi tujuan ke disk
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### Lihat Juga

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Menyisipkan salinan slide yang ditentukan ke posisi tertentu dalam koleksi.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Indeks slide baru. |
| sourceSlide | ISlide | Slide yang akan digandakan. |
| destLayout | ILayoutSlide | Slide tata letak untuk slide baru. |

### Nilai Kembalian

Slide yang disisipkan.

### Lihat Juga

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Menyisipkan salinan slide sumber yang ditentukan ke posisi tertentu dalam koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai, maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilemparkan (jika allowCloneMissingLayout bernilai false).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Indeks slide baru. |
| sourceSlide | ISlide | Slide yang akan digandakan. |
| destMaster | IMasterSlide | Master slide untuk slide baru. |
| allowCloneMissingLayout | Boolean | Jika tidak ada tata letak yang sesuai di master yang ditentukan maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilemparkan (jika allowCloneMissingLayout bernilai false). |

### Nilai Kembalian

Slide yang disisipkan.

### Pengecualian

| exception | condition |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Dilemparkan jika tidak ada tata letak yang sesuai di master yang ditentukan dan allowCloneMissingLayout bernilai false. |

### Lihat Juga

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->