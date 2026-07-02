---
title: Save
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menyimpan semua slide dalam presentasi ke file dengan format yang ditentukan.
type: docs
weight: 380
url: /id/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Menyimpan semua slide dalam presentasi ke sebuah file dengan format yang ditentukan.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Jalur ke file yang dibuat. |
| format | SaveFormat | Format data yang diekspor. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Menyimpan semua slide dalam presentasi ke aliran dengan format yang ditentukan.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran keluaran. |
| format | SaveFormat | Format data yang diekspor. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Menyimpan semua slide dalam presentasi ke sebuah file dengan format yang ditentukan dan opsi tambahan.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Jalur ke file yang dibuat. |
| format | SaveFormat | Format data yang diekspor. |
| options | ISaveOptions | Opsi format tambahan. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Menyimpan semua slide dalam presentasi ke aliran dengan format yang ditentukan dan opsi tambahan.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran keluaran. |
| format | SaveFormat | Format data yang diekspor. |
| options | ISaveOptions | Opsi format tambahan. |

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| NotSupportedException | Jika Anda mencoba menyimpan file terenkripsi dalam format selain Office 2007-2010 |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Menyimpan slide tertentu dalam presentasi ke sebuah file dengan format yang ditentukan.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Jalur ke file yang dibuat. |
| slides | Int32[] | Array dengan posisi slide, dimulai dari 1. |
| format | SaveFormat | Format data yang diekspor. |

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| ArgumentNullException | Ketika parameter stream atau slides bernilai null. |
| ArgumentOutOfRangeException | Ketika parameter slides berisi nomor halaman yang salah. |
| InvalidOperationException | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Menyimpan slide tertentu dalam presentasi ke sebuah file dengan format yang ditentukan.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Jalur ke file yang dibuat. |
| slides | Int32[] | Array dengan posisi slide, dimulai dari 1. |
| format | SaveFormat | Format data yang diekspor. |
| options | ISaveOptions | Opsi format tambahan. |

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| ArgumentNullException | Ketika parameter stream atau slides bernilai null. |
| ArgumentOutOfRangeException | Ketika parameter slides berisi nomor halaman yang salah. |
| InvalidOperationException | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Menyimpan slide tertentu dalam presentasi ke aliran dengan format yang ditentukan.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran keluaran. |
| slides | Int32[] | Array dengan posisi slide, dimulai dari 1. |
| format | SaveFormat | Format data yang diekspor. |

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| ArgumentNullException | Ketika parameter stream atau slides bernilai null. |
| ArgumentOutOfRangeException | Ketika parameter slides berisi nomor halaman yang salah. |
| InvalidOperationException | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Menyimpan slide tertentu dalam presentasi ke aliran dengan format yang ditentukan.

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

| Pengecualian | Kondisi |
| --- | --- |
| ArgumentNullException | Ketika parameter stream atau slides bernilai null. |
| ArgumentOutOfRangeException | Ketika parameter slides berisi nomor halaman yang salah. |
| InvalidOperationException | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Menyimpan semua slide dalam presentasi ke sekumpulan file yang mewakili markup XAML.

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

* antarmuka [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->