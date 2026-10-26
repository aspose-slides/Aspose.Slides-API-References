---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: ラップモードがバイナリの場合、ストリームから指定されたバイト数を読み取り、そうでない場合は指定された文字数を読み取り **uint8_t** 型に変換します。読み取り結果を指定されたバイト配列に書き込みます。
type: docs
weight: 66
url: /ja/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

ラップモードがバイナリの場合、ストリームから指定されたバイト数を読み取り、そうでない場合は指定された文字数を読み取り **uint8_t** 型に変換します。読み取り結果を指定されたバイト配列に書き込みます。

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列 |
| offset | **int32_t** | **buffer** の中で書き込みを開始する 0 ベースの位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイト数または文字数

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) メソッド

ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 読み取ったバイトを書き込むバイト配列ビュー |
| offset | **int32_t** | **buffer** の中で書き込みを開始する 0 ベースの位置 |
| count | **int32_t** | 読み取るバイト数 |

### 戻り値

読み取ったバイト数

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [BasicSTDIStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)