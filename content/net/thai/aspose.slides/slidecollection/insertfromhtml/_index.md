---
title: InsertFromHtml
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ
type: docs
weight: 140
url: /th/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlText | String | Html ที่จะเพิ่ม |
| resolver | IExternalResourceResolver | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด |
| uri | String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* อินเทอร์เฟซ [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlText | String | Html ที่จะเพิ่ม |
| resolver | IExternalResourceResolver | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด |
| uri | String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |
| useSlideWithIndexAsStart | Boolean | ธงนี้กำหนดวิธีการเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** จะเริ่มแทรกข้อมูลจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** จะเพิ่มข้อมูลลงในสไลด์ที่สร้างขึ้น |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* อินเทอร์เฟซ [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlText | String | Html ที่จะเพิ่ม |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlText | String | Html ที่จะเพิ่ม |
| useSlideWithIndexAsStart | Boolean | ธงนี้กำหนดวิธีการเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** จะเริ่มแทรกข้อมูลจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** จะเพิ่มข้อมูลลงในสไลด์ที่สร้างขึ้น |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlReader | TextReader | อ็อบเจกต์ TextReader ที่จะใช้เป็นแหล่งของไฟล์ HTML |
| resolver | IExternalResourceResolver | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด |
| uri | String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* อินเทอร์เฟซ [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlReader | TextReader | อ็อบเจกต์ TextReader ที่จะใช้เป็นแหล่งของไฟล์ HTML |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlStream | Stream | อ็อบเจกต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML |
| resolver | IExternalResourceResolver | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด |
| uri | String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* อินเทอร์เฟซ [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlStream | Stream | อ็อบเจกต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML |
| resolver | IExternalResourceResolver | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด |
| uri | String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |
| useSlideWithIndexAsStart | Boolean | ธงนี้กำหนดวิธีการเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** จะเริ่มแทรกข้อมูลจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** จะเพิ่มข้อมูลลงในสไลด์ที่สร้างขึ้น |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* อินเทอร์เฟซ [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlStream | Stream | อ็อบเจกต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | Int32 | ตำแหน่งที่จะทำการแทรก |
| htmlStream | Stream | อ็อบเจกต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML |
| useSlideWithIndexAsStart | Boolean | ธงนี้กำหนดวิธีการเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** จะเริ่มแทรกข้อมูลจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** จะเพิ่มข้อมูลลงในสไลด์ที่สร้างขึ้น |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ISlide](../../islide)
* คลาส [SlideCollection](../../slidecollection)
* เนมสเปซ [Aspose.Slides](../../slidecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->