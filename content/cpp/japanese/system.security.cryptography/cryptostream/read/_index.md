---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームからデータを読み取ります。
type: docs
weight: 14
url: /ja/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド


ストリームからデータを読み取ります。

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 送信先データバッファ。 |
| offset | **int32_t** | 送信先バッファ内のオフセット。 |
| count | **int32_t** | 読み取るバイト数。 |

### 戻り値

実際に読み取られるバイト数。

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド


ストリームからデータを読み取ります。

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 送信先データバッファ。 |
| offset | **int32_t** | 送信先バッファ内のオフセット。 |
| count | **int32_t** | 読み取るバイト数。 |

### 戻り値

実際に読み取られるバイト数。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [CryptoStream](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)