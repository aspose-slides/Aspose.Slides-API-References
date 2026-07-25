---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: ラッピングモードがバイナリの場合、指定されたバイト配列から指定されたサブレンジのバイトを書き込み、ストリームに送ります。バイナリでない場合は、指定されたバイト配列から指定されたサブレンジのバイトを char_type 型に変換し、その結果をストリームに書き込みます。
type: docs
weight: 79
url: /ja/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

バイナリラッピングモードの場合、指定されたバイト配列から指定されたサブレンジのバイトを書き込みストリームに送ります。それ以外の場合、指定されたバイト配列から指定されたサブレンジのバイトを `char_type` 型に変換し、結果をストリームに書き込みます。

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列 |
| offset | **int32_t** | **buffer** 内で書き込みが開始されるサブレンジの 0 ベースインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から指定されたサブレンジのバイトを書き込みストリームに送ります。

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイトを含む配列ビュー |
| offset | **int32_t** | **buffer** 内で書き込みが開始されるサブレンジの 0 ベースインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [BasicSTDOStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)