---
title: Save
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menyimpan semua slide dari presentasi ke file dengan format yang ditentukan.
type: docs
weight: 390
url: /id/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Menyimpan semua slide dari presentasi ke file dengan format yang ditentukan.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Jalur ke file yang dibuat. |
| format | SaveFormat | Format data yang diekspor. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Menyimpan semua slide dari presentasi ke aliran dalam format yang ditentukan.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran keluaran. |
| format | SaveFormat | Format data yang diekspor. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Menyimpan semua slide dari presentasi ke aliran dalam format yang ditentukan serta dengan opsi tambahan.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran keluaran. |
| format | SaveFormat | Format data yang diekspor. |
| options | ISaveOptions | Opsi format tambahan. |

### Pengecualian

| Pengecualian | kondisi |
| --- | --- |
| NotSupportedException | Jika Anda mencoba menyimpan file terenkripsi dalam format selain Office 2007-2010 |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Menyimpan semua slide dari presentasi ke sekumpulan file yang mewakili markup XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | IXamlOptions | Opsi format XAML. |

### Contoh

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Lihat Juga

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Menyimpan slide tertentu dari presentasi ke file dengan format yang ditentukan sambil mempertahankan nomor halaman.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Jalur ke file yang dibuat. |
| slides | Int32[] | Array dengan posisi slide, dimulai dari 1. |
| format | SaveFormat | Format data yang diekspor. |

### Pengecualian

| Pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Ketika parameter stream atau slides bernilai null. |
| ArgumentOutOfRangeException | Ketika parameter slides berisi nomor halaman yang salah. |
| InvalidOperationException | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Menyimpan slide tertentu dari presentasi ke file dengan format yang ditentukan sambil mempertahankan nomor halaman.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Jalur ke file yang dibuat. |
| slides | Int32[] | Array dengan posisi slide, dimulai dari 1. |
| format | SaveFormat | Format data yang diekspor. |
| options | ISaveOptions | Opsi format tambahan. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Menyimpan slide tertentu dari presentasi ke aliran dalam format yang ditentukan sambil mempertahankan nomor halaman.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran keluaran. |
| slides | Int32[] | Array dengan posisi slide, dimulai dari 1. |
| format | SaveFormat | Format data yang diekspor. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Menyimpan slide tertentu dari presentasi ke aliran dalam format yang ditentukan sambil mempertahankan nomor halaman.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran keluaran. |
| slides | Int32[] | Array dengan posisi slide, dimulai dari 1. |
| format | SaveFormat | Format data yang diekspor. |
| options | ISaveOptions | Opsi format tambahan. |

### Pengecualian

| Pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Ketika parameter stream atau slides bernilai null. |
| ArgumentOutOfRangeException | Ketika parameter slides berisi nomor halaman yang salah. |
| InvalidOperationException | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Contoh

Contoh berikut menunjukkan cara mengonversi PowerPoint ke PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Contoh berikut menunjukkan cara mengonversi PowerPoint ke PNG dengan dimensi khusus.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Contoh berikut menunjukkan cara mengonversi PowerPoint ke PNG dengan ukuran khusus.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->