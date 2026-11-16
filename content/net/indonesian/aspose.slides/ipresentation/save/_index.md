---
title: Save
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menyimpan semua slide presentasi ke sebuah file dengan format yang ditentukan.
type: docs
weight: 390
url: /id/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Menyimpan semua slide dari presentasi ke sebuah file dengan format yang ditentukan.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* perakitan [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Menyimpan semua slide dari presentasi ke aliran dalam format yang ditentukan.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* perakitan [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Menyimpan semua slide dari presentasi ke file dengan format yang ditentukan serta opsi tambahan.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* perakitan [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Menyimpan semua slide dari presentasi ke aliran dalam format yang ditentukan serta opsi tambahan.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Pengecualian

| Pengecualian | kondisi |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* perakitan [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Menyimpan slide tertentu dari presentasi ke file dengan format yang ditentukan.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### Pengecualian

| Pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* perakitan [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Menyimpan slide tertentu dari presentasi ke file dengan format yang ditentukan.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Pengecualian

| Pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* perakitan [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Menyimpan slide tertentu dari presentasi ke aliran dalam format yang ditentukan.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### Pengecualian

| Pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* perakitan [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Menyimpan slide tertentu dari presentasi ke aliran dalam format yang ditentukan serta opsi tambahan.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Pengecualian

| Pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lihat Juga

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* antarmuka [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* antarmuka [IPresentation](../../ipresentation)
* ruang nama [Aspose.Slides](../../ipresentation)
* perakitan [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Menyimpan semua slide dari presentasi ke sekumpulan file yang mewakili markup XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | IXamlOptions | The XAML format options. |

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
* perakitan [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->