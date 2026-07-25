---
title: Read()
second_title: Aspose.Slides for C++ APIリファレンス
description: ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。
type: docs
weight: 391
url: /ja/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むためのバイト配列 |
| offset | **int32_t** | **buffer** に書き込みを開始する0ベースの位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイト数

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 読み取ったバイトを書き込むためのバイト配列 |
| offset | **int32_t** | **buffer** に書き込みを開始する0ベースの位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイト数

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [SslStream](../)
* 名前空間 [System::Net::Security](../../)
* ライブラリ [Aspose.Slides](../../../)