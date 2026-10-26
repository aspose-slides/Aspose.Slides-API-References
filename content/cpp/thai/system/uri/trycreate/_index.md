---
title: TryCreate()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างวัตถุ Uri ที่แสดงถึง URI ที่ระบุ; อาร์กิวเมนต์ระบุประเภทของ URI.
type: docs
weight: 508
url: /th/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method

สร้างวัตถุ [Uri](../) ที่แสดงถึง URI ที่ระบุ; อาร์กิวเมนต์กำหนดประเภทของ URI

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | สตริง URI ที่จะแสดงโดยวัตถุที่กำลังก่อสร้าง |
| uriKind | [UriKind](../../urikind/) | ระบุประเภทของ URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | อาร์กิวเมนต์ผลลัพธ์ที่ถ้าการก่อสร้างสำเร็จจะชี้ไปยังวัตถุ [Uri](../) ที่สร้างใหม่เมื่อเมธอดคืนค่า |

### ค่าที่คืนกลับ

true ถ้าการก่อสร้างสำเร็จ, มิฉะนั้น - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method

สร้างวัตถุ [Uri](../) จาก [Uri](../) ที่ระบุซึ่งเป็นวัตถุที่แสดงถึง base URI และการแสดงผลเป็นสตริงของ relative URI

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI พื้นฐาน |
| relativeUri | const [String](../../string/)\& | relative URI ที่เพิ่มเข้าไปกับ base URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | อาร์กิวเมนต์ผลลัพธ์ที่ถ้าการก่อสร้างสำเร็จจะชี้ไปยังวัตถุ [Uri](../) ที่สร้างใหม่เมื่อเมธอดคืนค่า |

### ค่าที่คืนกลับ

true ถ้าการก่อสร้างสำเร็จ, มิฉะนั้น - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method

สร้างวัตถุ [Uri](../) จาก base URI และ relative URI ที่ระบุ

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI พื้นฐาน |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | relative URI ที่เพิ่มเข้าไปกับ base URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | อาร์กิวเมนต์ผลลัพธ์ที่ถ้าการก่อสร้างสำเร็จจะชี้ไปยังวัตถุ [Uri](../) ที่สร้างใหม่เมื่อเมธอดคืนค่า |

### ค่าที่คืนกลับ

true ถ้าการก่อสร้างสำเร็จ, มิฉะนั้น - false

## ดูเพิ่มเติม

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)