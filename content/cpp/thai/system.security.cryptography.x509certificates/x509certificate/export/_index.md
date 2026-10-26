---
title: Export()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งออกวัตถุปัจจุบันเป็นอาเรย์ของไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ดำเนินการ.
type: docs
weight: 287
url: /th/system.security.cryptography.x509certificates/x509certificate/export/
---
## X509Certificate::Export(X509ContentType) const เมธอด

ส่งออกวัตถุปัจจุบันเป็นอาเรย์ของไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ดำเนินการ.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | ระบุวิธีการจัดรูปแบบข้อมูลผลลัพธ์. |

### ค่าที่ส่งกลับ

อาเรย์ของไบต์ที่แสดงถึงวัตถุปัจจุบัน.

## X509Certificate::Export(X509ContentType, const SecureStringPtr\&) const เมธอด

ส่งออกวัตถุปัจจุบันเป็นอาเรย์ของไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ดำเนินการ.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const SecureStringPtr &password) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | ระบุวิธีการจัดรูปแบบข้อมูลผลลัพธ์. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | รหัสผ่านที่จำเป็นสำหรับการเข้าถึงข้อมูลใบรับรอง. |

### ค่าที่ส่งกลับ

อาเรย์ของไบต์ที่แสดงถึงวัตถุปัจจุบัน.

## X509Certificate::Export(X509ContentType, const String\&) const เมธอด

ส่งออกวัตถุปัจจุบันเป็นอาเรย์ของไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ดำเนินการ.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const String &password) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | ระบุวิธีการจัดรูปแบบข้อมูลผลลัพธ์. |
| password | const [String](../../../system/string/)\& | รหัสผ่านที่จำเป็นสำหรับการเข้าถึงข้อมูลใบรับรอง. |

### ค่าที่ส่งกลับ

อาเรย์ของไบต์ที่แสดงถึงวัตถุปัจจุบัน.

## ดูเพิ่มเติม

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)