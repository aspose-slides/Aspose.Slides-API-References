---
title: Save
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุ
type: docs
weight: 380
url: /th/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุ

```csharp
public void Save(string fname, SaveFormat format)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

```csharp
public void Save(Stream stream, SaveFormat format)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | สตรีมผลลัพธ์ |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกรูปแบบเพิ่มเติม |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

บันทึกสไลด์ทั้งหมดของงานนำเสนอไปยังสตรีมในรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | สตรีมผลลัพธ์ |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| NotSupportedException | หากพยายามบันทึกไฟล์ที่เข้ารหัสในรูปแบบที่ไม่ใช่ Office 2007-2010 |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุ

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | Int32[] | อาเรย์ที่มีตำแหน่งสไลด์ เริ่มจาก 1 |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentNullException | เมื่อพารามิเตอร์ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ไม่ถูกต้อง |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

บันทึกสไลด์ที่ระบุของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุ

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | Int32[] | อาเรย์ที่มีตำแหน่งสไลด์ เริ่มจาก 1 |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentNullException | เมื่อพารามิเตอร์ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ไม่ถูกต้อง |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

บันทึกสไลด์ที่ระบุของงานนำเข้าสู่สตรีมในรูปแบบที่ระบุ

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | สตรีมผลลัพธ์ |
| slides | Int32[] | อาเรย์ที่มีตำแหน่งสไลด์ เริ่มจาก 1 |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentNullException | เมื่อพารามิเตอร์ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ไม่ถูกต้อง |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

บันทึกสไลด์ที่ระบุของงานนำเข้าสู่สตรีมในรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | สตรีมผลลัพธ์ |
| slides | Int32[] | อาเรย์ที่มีตำแหน่งสไลด์ เริ่มจาก 1 |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentNullException | เมื่อพารามิเตอร์ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ไม่ถูกต้อง |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่เป็นการแทน XAML markup

```csharp
public void Save(IXamlOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | IXamlOptions | ตัวเลือกรูปแบบ XAML |

### ตัวอย่าง

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### ดูเพิ่มเติม

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->