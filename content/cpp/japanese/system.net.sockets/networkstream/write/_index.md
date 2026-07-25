---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたバイト配列から、指定されたバイトのサブレンジを書き込み、ストリームへ書き込みます。
type: docs
weight: 209
url: /ja/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から、指定されたバイトのサブレンジを書き込み、ストリームへ書き込みます。

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列です。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセットです。 |
| size | **int32_t** | 書き込むサブレンジの要素数です。 |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から、指定されたバイトのサブレンジを書き込み、ストリームへ書き込みます。

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイトを含む配列ビューです。 |
| offset | **int32_t** | 書き込みを開始する **buffer** 内の要素の 0 ベースインデックスです。 |
| size | **int32_t** | 書き込むサブレンジの要素数です。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [NetworkStream](../)
* 名前空間 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)