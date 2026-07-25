---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: 基になるストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。
type: docs
weight: 53
url: /ja/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

基になるストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列 |
| offset | **int32_t** | **buffer** に書き込みを開始する 0 から始まる位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイト数

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

基になるストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列 |
| offset | **int32_t** | **buffer** に書き込みを開始する 0 から始まる位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイト数

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [BufferedStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)