---
title: Uri()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอ็อบเจ็กต์ Uri ที่แสดงถึง URI ที่ระบุ
type: docs
weight: 287
url: /th/system/uri/uri/
---
## Uri::Uri(const String\&) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ [Uri](../) ที่แสดงถึง URI ที่ระบุ

```cpp
System::Uri::Uri(const String &uriString)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | สตริง URI ที่จะแสดงโดยอ็อบเจ็กต์ที่กำลังสร้าง |

## Uri::Uri(const String\&, bool) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ [Uri](../) ที่แสดงถึง URI ที่ระบุ; ทำให้กำหนดว่าควรทำการเอสเคป URI หรือไม่

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | สตริง URI ที่จะแสดงโดยอ็อบเจ็กต์ที่กำลังสร้าง |
| dontEscape | **bool** | ระบุว่าควรไม่ทำการเอสเคป URI หรือไม่ |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ [Uri](../) จากอ็อบเจ็กต์ [Uri](../) ที่ระบุซึ่งแสดงถึง URI พื้นฐานและการแทนสตริงของ URI เชิงสัมพันธ์; ทำให้กำหนดว่าควรทำการเอสเคป URI หรือไม่

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI พื้นฐาน |
| relativeUri | const [String](../../string/)\& | URI เชิงสัมพันธ์ที่ถูกเพิ่มเข้าไปใน URI พื้นฐาน |
| dontEscape | **bool** | ระบุว่าควรไม่ทำการเอสเคป URI หรือไม่ |

## Uri::Uri(const String\&, UriKind) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ [Uri](../) ที่แสดงถึง URI ที่ระบุ; ทำให้กำหนดประเภทของ URI

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | สตริง URI ที่จะแสดงโดยอ็อบเจ็กต์ที่กำลังสร้าง |
| uriKind | [UriKind](../../urikind/) | ระบุประเภทของ URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ [Uri](../) จาก URI พื้นฐานและ URI เชิงสัมพันธ์ที่ระบุ

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI พื้นฐาน |
| relativeUri | const [String](../../string/)\& | URI เชิงสัมพันธ์ที่ถูกเพิ่มเข้าไปใน URI พื้นฐาน |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ [Uri](../) จาก URI พื้นฐานและ URI เชิงสัมพันธ์ที่ระบุ

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI พื้นฐาน |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI เชิงสัมพันธ์ที่ถูกเพิ่มเข้าไปใน URI พื้นฐาน |

## ดูเพิ่มเติม

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)