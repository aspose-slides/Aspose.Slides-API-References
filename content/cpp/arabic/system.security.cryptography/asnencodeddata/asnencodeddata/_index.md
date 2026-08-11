---
title: AsnEncodedData()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: منشئ النسخ.
type: docs
weight: 1
url: /ar/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) منشئ

منشئ النسخ.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) لنسخ البيانات من. |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) منشئ

منشئ.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات المشفرة بتنسيق بايت خام. |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) منشئ

منشئ.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) معرف البيانات المشفرة. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات المشفرة بتنسيق بايت خام. |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) منشئ

منشئ.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) معرف البيانات المشفرة. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات المشفرة بتنسيق بايت خام. |

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* فئة [AsnEncodedData](../)
* فئة [Oid](../../oid/)
* فئة [String](../../../system/string/)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)