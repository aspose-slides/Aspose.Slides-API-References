---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。
type: docs
weight: 27
url: /ja/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### 戻り値

The number of bytes read

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The byte array view to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### 戻り値

The number of bytes read

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| N | The size of the stack array |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | The byte stack array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### 戻り値

The number of bytes read

## Stream::Read(const System::Span\<uint8_t\>\&) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト スパンに書き込みます。

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | The byte span to write the read bytes to |

### 戻り値

The number of bytes read

## 参照

* typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [Stream](../)
* クラス [Span](../../../system/span/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)