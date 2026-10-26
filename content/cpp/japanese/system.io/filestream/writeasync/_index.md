---
title: WriteAsync()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のストリームにバイト列を非同期で書き込み、書き込まれたバイト数だけこのストリーム内の現在位置を進め、キャンセル要求を監視します。
type: docs
weight: 261
url: /ja/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) メソッド

現在のストリームにバイト列を非同期で書き込み、書き込まれたバイト数だけこのストリーム内の現在位置を進め、キャンセル要求を監視します。

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列です。 |
| offset | **int32_t** | 書き込みサブレンジが開始する **buffer** 内の 0 ベースインデックスです。 |
| count | **int32_t** | 書き込むサブレンジ内の要素数です。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | キャンセル要求を監視するトークンです。 |

### 戻り値

非同期書き込み操作を表すタスクです。

## 参照

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [CancellationToken](../../../system.threading/cancellationtoken/)
* クラス [FileStream](../)
* 名前空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)