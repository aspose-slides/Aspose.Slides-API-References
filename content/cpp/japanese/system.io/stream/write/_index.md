---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたバイト配列から指定されたバイトのサブレンジを書き込み、ストリームに送ります。
type: docs
weight: 53
url: /ja/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から指定されたバイトのサブレンジを書き込み、ストリームに送ります。

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列 |
| offset | **int32_t** | 書き込むサブレンジが開始する **buffer** 内の要素の 0 始まりインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から指定されたバイトのサブレンジを書き込み、ストリームに送ります。

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイトを含む配列ビュー |
| offset | **int32_t** | 書き込むサブレンジが開始する **buffer** 内の要素の 0 始まりインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から指定されたバイトのサブレンジを書き込み、ストリームに送ります。

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| N | スタック配列のサイズ |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | 書き込むバイトを含むスタック配列 |
| offset | **int32_t** | 書き込むサブレンジが開始する **buffer** 内の要素の 0 始まりインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) メソッド

指定されたバイトスパンから指定されたバイトのサブレンジを書き込み、ストリームに送ります。

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | 書き込まれたバイトを読み取るバイトスパン |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)