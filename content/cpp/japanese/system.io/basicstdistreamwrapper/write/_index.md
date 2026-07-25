---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: ラッピングモードがバイナリの場合、指定されたバイト配列から指定されたバイト範囲をストリームに書き込みます。バイナリでない場合、指定されたバイト配列から指定されたバイト範囲を char_type 型に変換し、その結果をストリームに書き込みます。サポートされていません！
type: docs
weight: 79
url: /ja/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

ラッピングモードがバイナリの場合、指定されたバイト配列から指定されたバイト範囲をストリームに書き込みます。バイナリでない場合、指定されたバイト配列から指定されたバイト範囲を char_type 型に変換し、その結果をストリームに書き込みます。サポートされていません！

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列。 |
| offset | **int32_t** | **buffer** の中で書き込みが開始されるサブレンジの 0 から始まるインデックス。 |
| count | **int32_t** | 書き込むサブレンジ内の要素数。 |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

指定されたバイト配列から指定されたバイト範囲をストリームに書き込みます。

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイトを含む配列ビュー |
| offset | **int32_t** | **buffer** の中で書き込みが開始されるサブレンジの 0 から始まるインデックス |
| count | **int32_t** | 書き込むサブレンジ内の要素数 |

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [BasicSTDIStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)