---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: ラッピングモードが binary の場合、指定されたバイト配列から指定されたバイトのサブレンジをストリームに書き込みます。それ以外の場合、指定されたバイト配列から指定されたバイトのサブレンジを char_type 型に変換し、結果をストリームに書き込みます。
type: docs
weight: 79
url: /ja/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

ラッピングモードが binary の場合、指定されたバイト配列から指定されたバイトのサブレンジをストリームに書き込みます。それ以外の場合、指定されたバイト配列から指定されたバイトのサブレンジを char_type 型に変換し、結果をストリームに書き込みます。

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列 |
| offset | **int32_t** | **buffer** 内で書き込みサブレンジが開始する 0 ベースのインデックス |
| count | **int32_t** | 書き込み対象のサブレンジ内の要素数 |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から指定されたバイトのサブレンジをストリームに書き込みます。

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイトを含む配列ビュー |
| offset | **int32_t** | **buffer** 内で書き込みサブレンジが開始する 0 ベースのインデックス |
| count | **int32_t** | 書き込み対象のサブレンジ内の要素数 |

## 参照

* typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [BasicSTDIOStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)