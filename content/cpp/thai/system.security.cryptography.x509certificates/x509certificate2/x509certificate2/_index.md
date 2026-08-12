---
title: X509Certificate2()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้าง X509Certificate2 ว่างเปล่า.
type: docs
weight: 1
url: /th/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() constructor

สร้าง [X509Certificate2](../) ว่างเปล่า.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ไฟล์สำหรับโหลดใบรับรองจาก |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | อ็อบเจ็กต์ [X509Certificate](../../x509certificate/) |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลำดับของไบต์ที่เป็นตัวแทนของใบรับรองที่เข้ารหัส |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลำดับของไบต์ที่เป็นตัวแทนของใบรับรองที่เข้ารหัส |
| password | const [String](../../../system/string/)\& | รหัสผ่านของใบรับรอง |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลำดับของไบต์ที่เป็นตัวแทนของใบรับรองที่เข้ารหัส |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | รหัสผ่านของใบรับรอง |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลำดับของไบต์ที่เป็นตัวแทนของใบรับรองที่เข้ารหัส |
| password | const [String](../../../system/string/)\& | รหัสผ่านของใบรับรอง |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | แฟล็กที่ระบุวิธีการจัดเก็บคีย์ |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลำดับของไบต์ที่เป็นตัวแทนของใบรับรองที่เข้ารหัส |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | รหัสผ่านของใบรับรอง |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | แฟล็กที่ระบุวิธีการจัดเก็บคีย์ |

## X509Certificate2::X509Certificate2(const String\&, const String\&) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ไฟล์สำหรับโหลดใบรับรองจาก |
| password | const [String](../../../system/string/)\& | รหัสผ่านของใบรับรอง |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ไฟล์สำหรับโหลดใบรับรองจาก |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | รหัสผ่านของใบรับรอง |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ไฟล์สำหรับโหลดใบรับรองจาก |
| password | const [String](../../../system/string/)\& | รหัสผ่านของใบรับรอง |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | แฟล็กที่ระบุวิธีการจัดเก็บคีย์ |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ไฟล์สำหรับโหลดใบรับรองจาก |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | รหัสผ่านของใบรับรอง |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | แฟล็กที่ระบุวิธีการจัดเก็บคีย์ |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) constructor

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลำดับของไบต์ที่เป็นตัวแทนของใบรับรองที่เข้ารหัส (ส่วนสาธารณะ) |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลำดับของไบต์ที่เป็นตัวแทนของคีย์ส่วนตัว |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | แฟล็กที่ระบุวิธีการจัดเก็บคีย์ |

## ดูเพิ่มเติม

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)