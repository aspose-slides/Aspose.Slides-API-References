---
title: ReadAsync()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のストリームからバイトのシーケンスを非同期的に読み取り、読み取ったバイト数だけストリーム内の位置を進め、キャンセル要求を監視します。
type: docs
weight: 40
url: /ja/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) メソッド

現在のストリームからバイトのシーケンスを非同期的に読み取り、読み取ったバイト数だけストリーム内の位置を進め、キャンセル要求を監視します。

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むためのバイト配列。 |
| offset | **int32_t** | 0 ベースの位置で、**buffer** に書き込みを開始する位置。 |
| count | **int32_t** | 読み取るバイト数。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | キャンセル要求を監視するトークン。 |

### 戻り値

非同期読み取り操作を表すタスク。TResult パラメーターの値にはバッファに読み取られたバイト総数が含まれます。利用可能なバイト数が要求された数未満の場合や、ストリームの終端に達した場合は、結果の値は要求されたバイト数未満になることがあり、0（ゼロ）になることもあります。

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

現在のストリームからバイトのシーケンスを非同期的に読み取り、読み取ったバイト数だけストリーム内の位置を進め、キャンセル要求を監視します。

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むためのバイト配列。 |
| offset | **int32_t** | 0 ベースの位置で、**buffer** に書き込みを開始する位置。 |
| count | **int32_t** | 読み取るバイト数。 |

### 戻り値

非同期読み取り操作を表すタスク。TResult パラメーターの値にはバッファに読み取られたバイト総数が含まれます。利用可能なバイト数が要求された数未満の場合や、ストリームの終端に達した場合は、結果の値は要求されたバイト数未満になることがあり、0（ゼロ）になることもあります。

## 参照

* 型定義 [RTaskPtr](../../../system/rtaskptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [CancellationToken](../../../system.threading/cancellationtoken/)
* クラス [Stream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)