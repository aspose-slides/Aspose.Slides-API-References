---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。
type: docs
weight: 79
url: /ja/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド


ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列 |
| offset | **int32_t** | **buffer** の書き込み開始位置（0 ベース） |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取られたバイト数

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド


ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列ビュー |
| offset | **int32_t** | **buffer** の書き込み開始位置（0 ベース） |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取られたバイト数

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [MemoryStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)