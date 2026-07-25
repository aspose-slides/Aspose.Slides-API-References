---
title: FlushAsync()
second_title: Aspose.Slides for C++ API リファレンス
description: このストリームのすべてのバッファを非同期的にクリアし、バッファリングされたデータを基礎となるデバイスに書き込み、キャンセル要求を監視します。
type: docs
weight: 118
url: /ja/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) メソッド


このストリームのすべてのバッファを非同期的にクリアし、バッファリングされたデータを基礎となるデバイスに書き込み、キャンセル要求を監視します。

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | キャンセル要求を監視するためのトークンです。 |

### 戻り値

非同期フラッシュ操作を表すタスクです。

## Stream::FlushAsync() メソッド


このストリームのすべてのバッファを非同期的にクリアし、バッファリングされたデータを基礎となるデバイスに書き込み、キャンセル要求を監視します。

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### 戻り値

非同期フラッシュ操作を表すタスクです。

## 参照

* Typedef [TaskPtr](../../../system/taskptr/)
* クラス [CancellationToken](../../../system.threading/cancellationtoken/)
* クラス [Stream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)