---
title: ComputeHash()
second_title: Aspose.Slides for C++ API リファレンス
description: バッファのハッシュを計算します。
type: docs
weight: 14
url: /ja/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) メソッド

バッファのハッシュを計算します。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ソースバッファ。 |

### 戻り値

計算されたハッシュ値。

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) メソッド

バッファスライスのハッシュを計算します。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ソースバッファ。 |
| offset | int | ソースバッファ内のオフセット。 |
| count | int | ソースバッファから使用するバイト数。 |

### 戻り値

計算されたハッシュ値。

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) メソッド

ストリームの末尾まで読み取り、読み取ったデータのハッシュを計算します。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | データを読み取るストリーム。 |

### 戻り値

全ストリームデータの計算されたハッシュ値。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [HashAlgorithm](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)