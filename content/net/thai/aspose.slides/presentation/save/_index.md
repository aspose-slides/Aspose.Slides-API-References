---
title: Save
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังไฟล์ด้วยรูปแบบที่ระบุ
type: docs
weight: 400
url: /th/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุ

```csharp
public void Save(string fname, SaveFormat format)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในสตรีมด้วยรูปแบบที่ระบุ

```csharp
public void Save(Stream stream, SaveFormat format)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในสตรีมด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่เป็น XAML markup

```csharp
public void Save(IXamlOptions options)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | IXamlOptions | The XAML format options. |

### ตัวอย่าง

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุพร้อมคงเลขหน้า

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุพร้อมคงเลขหน้า

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในสตรีมด้วยรูปแบบที่ระบุพร้อมคงเลขหน้า

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในสตรีมด้วยรูปแบบที่ระบุพร้อมคงเลขหน้า

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### ตัวอย่าง

The following example shows how to convert PowerPoint to PNG.

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

The following example shows how to convert PowerPoint to PNG with custom dimensions.

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

The following example shows how to convert PowerPoint to PNG with custom size.

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

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->