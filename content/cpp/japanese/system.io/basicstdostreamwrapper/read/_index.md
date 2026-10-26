---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: ラッピングモードがバイナリの場合、ストリームから指定されたバイト数を読み取り、それ以外の場合は指定された文字数を読み取り、uint8_t 型に変換します。読み取り結果を指定されたバイト配列に書き込みます。サポートされていません！
type: docs
weight: 66
url: /ja/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

ラッピングモードがバイナリの場合、ストリームから指定されたバイト数を読み取ります。それ以外の場合は、指定された文字数を読み取り、**uint8_t** 型に変換します。読み取り結果を指定されたバイト配列に書き込みます。サポートされていません！

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列 |
| offset | **int32_t** | **buffer** の0ベース位置で、書き込みを開始する位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイトまたは文字数

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列ビュー |
| offset | **int32_t** | **buffer** の0ベース位置で、書き込みを開始する位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイト数

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [BasicSTDOStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)