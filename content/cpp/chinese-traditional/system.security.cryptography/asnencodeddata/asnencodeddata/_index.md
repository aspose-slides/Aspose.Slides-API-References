---
title: AsnEncodedData()
second_title: Aspose.Slides for C++ API 參考文件
description: 複製建構函式。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) constructor

複製建構函式。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) to copy data from. |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) constructor

建構函式。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Encoded data in raw byte format. |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) constructor

建構函式。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) identifier of encoded data. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Encoded data in raw byte format. |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) constructor

建構函式。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identifier of encoded data. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Encoded data in raw byte format. |

## 另請參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../)
* Class [Oid](../../oid/)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)