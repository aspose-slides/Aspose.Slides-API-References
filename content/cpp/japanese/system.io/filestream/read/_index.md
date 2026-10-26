---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。
type: docs
weight: 183
url: /ja/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト数をストリームから読み取り、指定されたバイト配列に書き込みます。

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列。 |
| offset | **int32_t** | **buffer** の 0 から始まる書き込み開始位置。 |
| count | **int32_t** | 読み取るバイト数。 |

### 戻り値

読み取られたバイト数。

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

指定されたバイト数をストリームから読み取り、指定されたバイト配列に書き込みます。

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列ビュー。 |
| offset | **int32_t** | **buffer** の 0 から始まる書き込み開始位置。 |
| count | **int32_t** | 読み取るバイト数。 |

### 戻り値

読み取られたバイト数。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [FileStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)