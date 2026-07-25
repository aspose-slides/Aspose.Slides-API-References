---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定したバイト配列から、ストリームへ指定されたバイトのサブレンジを書き込みます。
type: docs
weight: 92
url: /ja/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

指定したバイト配列から、ストリームへ指定されたバイトのサブレンジを書き込みます。

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列 |
| offset | **int32_t** | 書き込みサブレンジが始まる **buffer** 内の 0 ベースインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

指定したバイト配列から、ストリームへ指定されたバイトのサブレンジを書き込みます。

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイトを含む配列ビュー |
| offset | **int32_t** | 書き込みサブレンジが始まる **buffer** 内の 0 ベースインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [MemoryStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)