---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたバイト配列から、指定されたバイトのサブレンジを書き込み、基になるストリームに送ります。
type: docs
weight: 66
url: /ja/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


指定されたバイト配列から、指定されたバイトのサブレンジを書き込み、基になるストリームに送ります。

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列 |
| offset | **int32_t** | 書き込みを開始するサブレンジの **buffer** 内の 0 ベースインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


指定されたバイト配列から、指定されたバイトのサブレンジを書き込み、基になるストリームに送ります。

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイトを含む配列 |
| offset | **int32_t** | 書き込みを開始するサブレンジの **buffer** 内の 0 ベースインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [BufferedStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)