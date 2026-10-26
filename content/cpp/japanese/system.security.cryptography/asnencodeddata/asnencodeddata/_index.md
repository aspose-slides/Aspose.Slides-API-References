---
title: AsnEncodedData()
second_title: Aspose.Slides for C++ API リファレンス
description: コピーコンストラクタ。
type: docs
weight: 1
url: /ja/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) constructor

コピーコンストラクタ。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) コピー元のデータ。 |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) constructor

コンストラクタ。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 生のバイト形式のエンコードデータ。 |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) constructor

コンストラクタ。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) エンコードデータの識別子。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 生のバイト形式のエンコードデータ。 |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) constructor

コンストラクタ。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) エンコードデータの識別子。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 生のバイト形式のエンコードデータ。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [AsnEncodedData](../)
* クラス [Oid](../../oid/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)