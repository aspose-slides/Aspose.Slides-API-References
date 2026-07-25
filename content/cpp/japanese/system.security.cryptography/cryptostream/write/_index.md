---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームにデータを書き込みます。
type: docs
weight: 27
url: /ja/system.security.cryptography/cryptostream/write/
---
## CryptoStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド


Writes data to stream.

```cpp
void System::Security::Cryptography::CryptoStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ソースデータバッファ。 |
| offset | **int32_t** | ソースバッファ内のオフセット。 |
| count | **int32_t** | 書き込むバイト数。 |

## CryptoStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド


Writes data to stream.

```cpp
void System::Security::Cryptography::CryptoStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | ソースデータバッファ。 |
| offset | **int32_t** | ソースバッファ内のオフセット。 |
| count | **int32_t** | 書き込むバイト数。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [CryptoStream](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)