---
title: GetBytes()
second_title: Aspose.Slides for C++ API リファレンス
description: 既存の配列要素をランダムバイトで埋めます。
type: docs
weight: 14
url: /ja/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) メソッド

既存の配列要素をランダムバイトで埋めます。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 埋めるバイト配列。 |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) メソッド

既存の配列スライスをランダムバイトで埋めます。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | スライスを埋めるバイト配列。 |
| offset | int | スライス開始インデックス。 |
| count | int | スライスサイズ。 |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) メソッド

既存の配列ビュー要素をランダムバイトで埋めます。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 埋めるバイト配列ビュー。 |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) メソッド

既存の配列ビューのスライスをランダムバイトで埋めます。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | スライスを埋めるバイト配列ビュー。 |
| offset | int | スライス開始インデックス。 |
| count | int | スライスサイズ。 |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) メソッド

既存のスタック配列要素をランダムバイトで埋めます。

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 埋めるバイトスタック配列。 |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) メソッド

既存のスタック配列のスライスをランダムバイトで埋めます。

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | スライスを埋めるバイトスタック配列。 |
| offset | int | スライス開始インデックス。 |
| count | int | スライスサイズ。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RandomNumberGenerator](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)