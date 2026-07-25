---
title: FlushAsync()
second_title: Aspose.Slides for C++ API リファレンス
description: このストリームのすべてのバッファを非同期にクリアし、バッファされたデータを基になるデバイスに書き込み、キャンセル要求を監視します。
type: docs
weight: 157
url: /ja/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) メソッド


このストリームのすべてのバッファを非同期にクリアし、バッファされたデータを基になるデバイスに書き込み、キャンセル要求を監視します。

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | キャンセル要求を監視するトークン。 |

### 戻り値

非同期フラッシュ操作を表す Task。

## 参照

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)