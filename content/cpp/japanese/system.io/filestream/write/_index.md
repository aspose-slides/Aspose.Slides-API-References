---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたバイト配列から、指定されたバイトのサブレンジを書き込み、ストリームへ出力します。
type: docs
weight: 248
url: /ja/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から、指定されたバイトのサブレンジを書き込み、ストリームへ出力します。

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列。 |
| offset | **int32_t** | 書き込むサブレンジが開始する **buffer** 内の要素の 0 基準インデックス。 |
| count | **int32_t** | 書き込むサブレンジ内の要素数。 |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト配列から、指定されたバイトのサブレンジを書き込み、ストリームへ出力します。

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 書き込むバイトを含む配列ビュー。 |
| offset | **int32_t** | 書き込むサブレンジが開始する **buffer** 内の要素の 0 基準インデックス。 |
| count | **int32_t** | 書き込むサブレンジ内の要素数。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [FileStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)