---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。
type: docs
weight: 144
url: /ja/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列 |
| offset | **int32_t** | **buffer** の0ベースの位置で、書き込みを開始する位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイト数

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列ビュー |
| offset | **int32_t** | **buffer** の0ベースの位置で、書き込みを開始する位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイト数

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [UnmanagedMemoryStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)