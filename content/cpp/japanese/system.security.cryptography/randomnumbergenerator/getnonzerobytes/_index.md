---
title: GetNonZeroBytes()
second_title: Aspose.Slides for C++ API リファレンス
description: 既存の配列要素をランダムな非ゼロバイトで埋めます。
type: docs
weight: 27
url: /ja/system.security.cryptography/randomnumbergenerator/getnonzerobytes/
---
## RandomNumberGenerator::GetNonZeroBytes(ArrayPtr\<uint8_t\>) メソッド

既存の配列要素をランダムな非ゼロバイトで埋めます。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(ArrayPtr<uint8_t> bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列を埋めます。 |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView\<uint8_t\>) メソッド

既存の配列ビュー要素をランダムな非ゼロバイトで埋めます。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView<uint8_t> bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | バイト配列ビューを埋めます。 |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray\<uint8_t, N\>\&) メソッド

既存のスタック配列要素をランダムな非ゼロバイトで埋めます。

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | バイトスタック配列を埋めます。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [RandomNumberGenerator](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)