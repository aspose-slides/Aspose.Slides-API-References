---
title: StringWriter()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่ของ StringWriter โดยใช้ StringBuilder และ IFormatProvider ที่ระบุ
type: docs
weight: 1
url: /th/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [StringWriter](../) โดยใช้ StringBuilder ที่ระบุและ [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | อ็อบเจ็กต์ StringBuilder ที่จะใช้โดย [StringWriter](../) ที่กำลังสร้าง |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | อ็อบเจ็กต์ [IFormatProvider](../../../system/iformatprovider/) ที่จะใช้โดยอ็อบเจ็กต์ที่กำลังสร้าง |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [StringWriter](../) โดยใช้ StringBuilder ที่ระบุและ [IFormatProvider](../../../system/iformatprovider/) จากวัฒนธรรมปัจจุบัน.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | อ็อบเจ็กต์ StringBuilder ที่จะใช้โดย [StringWriter](../) ที่กำลังสร้าง |

## StringWriter::StringWriter(const IFormatProviderPtr\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [StringWriter](../) โดยใช้ [IFormatProvider](../../../system/iformatprovider/) ที่ระบุ.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | อ็อบเจ็กต์ [IFormatProvider](../../../system/iformatprovider/) ที่จะใช้โดยอ็อบเจ็กต์ที่กำลังสร้าง |

## StringWriter::StringWriter() คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [StringWriter](../) โดยใช้ [IFormatProvider](../../../system/iformatprovider/) จากวัฒนธรรมปัจจุบัน.

```cpp
System::IO::StringWriter::StringWriter()
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)