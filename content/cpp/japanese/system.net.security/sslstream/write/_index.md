---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたバイト配列をストリームに書き込みます。
type: docs
weight: 404
url: /ja/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) メソッド

指定されたバイト配列を書き込みます。

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイト配列。 |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から、指定されたバイトのサブレンジを書き込みます。

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列。 |
| offset | **int32_t** | 書き込みサブレンジが開始する **buffer** 内の要素の0ベースインデックス。 |
| count | **int32_t** | 書き込むサブレンジの要素数。 |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) メソッド

指定されたバイト配列を書き込みます。

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイト配列。 |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から、指定されたバイトのサブレンジを書き込みます。

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイトを含む配列。 |
| offset | **int32_t** | 書き込みサブレンジが開始する **buffer** 内の要素の0ベースインデックス。 |
| count | **int32_t** | 書き込むサブレンジの要素数。 |

## 参照項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [SslStream](../)
* 名前空間 [System::Net::Security](../../)
* ライブラリ [Aspose.Slides](../../../)