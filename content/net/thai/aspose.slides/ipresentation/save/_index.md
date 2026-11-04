---
title: Save
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ
type: docs
weight: 390
url: /th/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ

```csharp
public void Save(string fname, SaveFormat format)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [IPresentation](../../ipresentation)
* เนมสเปซ [Aspose.Slides](../../ipresentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมด้วยรูปแบบที่ระบุ

```csharp
public void Save(Stream stream, SaveFormat format)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | สตรีมเอาต์พุต |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [IPresentation](../../ipresentation)
* เนมสเปซ [Aspose.Slides](../../ipresentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม

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
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* อินเทอร์เฟซ [IPresentation](../../ipresentation)
* เนมสเปซ [Aspose.Slides](../../ipresentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | สตรีมเอาต์พุต |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| NotSupportedException | หากคุณพยายามบันทึกไฟล์ที่ถูกเข้ารหัสในรูปแบบที่ไม่ใช่ Office 2007-2010 |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* อินเทอร์เฟซ [IPresentation](../../ipresentation)
* เนมสเปซ [Aspose.Slides](../../ipresentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | Int32[] | อาเรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentNullException | เมื่อ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ผิด |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่สนับสนุน เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [IPresentation](../../ipresentation)
* เนมสเปซ [Aspose.Slides](../../ipresentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | String | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | Int32[] | อาเรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentNullException | เมื่อ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ผิด |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่สนับสนุน เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* อินเทอร์เฟซ [IPresentation](../../ipresentation)
* เนมสเปซ [Aspose.Slides](../../ipresentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | สตรีมเอาต์พุต |
| slides | Int32[] | อาเรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentNullException | เมื่อ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ผิด |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่สนับสนุน เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [IPresentation](../../ipresentation)
* เนมสเปซ [Aspose.Slides](../../ipresentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | Stream | สตรีมเอาต์พุต |
| slides | Int32[] | อาเรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | SaveFormat | รูปแบบของข้อมูลที่ส่งออก |
| options | ISaveOptions | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentNullException | เมื่อ stream หรือ slides มีค่า null |
| ArgumentOutOfRangeException | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าที่ผิด |
| InvalidOperationException | เมื่อใช้ SaveFormat ที่ไม่สนับสนุน เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |

### ดูเพิ่มเติม

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* อินเทอร์เฟซ [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* อินเทอร์เฟซ [IPresentation](../../ipresentation)
* เนมสเปซ [Aspose.Slides](../../ipresentation)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่แสดงรูปแบบ XAML

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

* อินเทอร์เฟซ [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* อินเทอร์เฟซ [IPresentation](../../ipresentation)
* เนมสเปซ [Aspose.Slides](../../ipresentation)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->