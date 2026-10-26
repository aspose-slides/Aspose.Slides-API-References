---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。
type: docs
weight: 196
url: /ja/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトが書き込まれるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 読み取るバイト数。 |

### 戻り値

読み取られたバイト数。

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 読み取ったバイトを書き込むためのバイト配列ビュー。 |
| offset | **int32_t** | **buffer** の書き込み開始位置（0ベース）。 |
| size | **int32_t** | 読み取るバイト数。 |

### 戻り値

読み取られたバイト数。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [NetworkStream](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)