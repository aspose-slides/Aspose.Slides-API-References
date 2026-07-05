---
title: Save
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในไฟล์ตามรูปแบบที่ระบุ.
type: docs
weight: 390
url: /th/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในไฟล์ตามฟอร์แมตที่ระบุ

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| format | SaveFormat | ฟอร์แมตของข้อมูลที่ส่งออก |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในสตรีมตามฟอร์แมตที่ระบุ

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | สตรีมผลลัพธ์ |
| format | SaveFormat | ฟอร์แมตของข้อมูลที่ส่งออก |

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

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในสตรีมตามฟอร์แมตที่ระบุและด้วยตัวเลือกเพิ่มเติม

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | สตรีมผลลัพธ์ |
| format | SaveFormat | ฟอร์แมตของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกฟอร์แมตเพิ่มเติม |

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| NotSupportedException | หากพยายามบันทึกไฟล์ที่เข้ารหัสในฟอร์แมตที่ไม่ใช่ Office 2007-2010 |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่แสดง XAML markup

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IXamlOptions | ตัวเลือกฟอร์แมต XAML |

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

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในไฟล์ตามฟอร์แมตที่ระบุโดยคงหมายเลขหน้า

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | Int32[] | อาร์เรย์ที่มีตำแหน่งสไลด์ เริ่มต้นจาก 1 |
| format | SaveFormat | ฟอร์แมตของข้อมูลที่ส่งออก |

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| ArgumentNullException | เมื่อพารามิเตอร์ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ไม่ถูกต้อง |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในไฟล์ตามฟอร์แมตที่ระบุโดยคงหมายเลขหน้า

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | Int32[] | อาร์เรย์ที่มีตำแหน่งสไลด์ เริ่มต้นจาก 1 |
| format | SaveFormat | ฟอร์แมตของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกฟอร์แมตเพิ่มเติม |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในสตรีมตามฟอร์แมตที่ระบุโดยคงหมายเลขหน้า

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | สตรีมผลลัพธ์ |
| slides | Int32[] | อาร์เรย์ที่มีตำแหน่งสไลด์ เริ่มต้นจาก 1 |
| format | SaveFormat | ฟอร์แมตของข้อมูลที่ส่งออก |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* คลาส [Presentation](../../presentation)
* เนมสเปซ [Aspose.Slides](../../presentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในสตรีมตามฟอร์แมตที่ระบุโดยคงหมายเลขหน้า

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | สตรีมผลลัพธ์ |
| slides | Int32[] | อาร์เรย์ที่มีตำแหน่งสไลด์ เริ่มต้นจาก 1 |
| format | SaveFormat | ฟอร์แมตของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกฟอร์แมตเพิ่มเติม |

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| ArgumentNullException | เมื่อพารามิเตอร์ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ไม่ถูกต้อง |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PNG

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

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PNG พร้อมการกำหนดมิติที่กำหนดเอง

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

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PNG ด้วยขนาดที่กำหนดเอง

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