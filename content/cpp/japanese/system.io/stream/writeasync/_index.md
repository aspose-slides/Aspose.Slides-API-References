---
title: WriteAsync()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期的にバイト列を書き込み、書き込まれたバイト数だけこのストリーム内の現在位置を進め、キャンセル要求を監視します。
type: docs
weight: 66
url: /ja/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) メソッド


非同期的にバイト列を書き込み、書き込まれたバイト数だけこのストリーム内の現在位置を進め、キャンセル要求を監視します。

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列です。 |
| offset | **int32_t** | **buffer** 内で書き込みサブレンジが開始する要素の 0 ベースインデックスです。 |
| count | **int32_t** | 書き込むサブレンジ内の要素数です。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | キャンセル要求を監視するトークンです。 |

### 戻り値

非同期書き込み操作を表すタスクです。

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド


非同期的にバイト列を書き込み、書き込まれたバイト数だけこのストリーム内の現在位置を進め、キャンセル要求を監視します。

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列です。 |
| offset | **int32_t** | **buffer** 内で書き込みサブレンジが開始する要素の 0 ベースインデックスです。 |
| count | **int32_t** | 書き込むサブレンジ内の要素数です。 |

### 戻り値

非同期書き込み操作を表すタスクです。

## 参照

* 型定義 [TaskPtr](../../../system/taskptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [CancellationToken](../../../system.threading/cancellationtoken/)
* クラス [Stream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)