---
title: Wait()
second_title: Aspose.Slides の C++ API リファレンス
description: キャンセルをサポートしながら、タスクが完了するのを待ちます。
type: docs
weight: 183
url: /ja/system.threading.tasks/task/wait/
---
## Task::Wait(const CancellationToken\&) メソッド

タスクが完了するまで待機します（キャンセルをサポート）。

```cpp
void System::Threading::Tasks::Task::Wait(const CancellationToken &cancellationToken)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | 待機中にキャンセルを監視するトークン |

## Task::Wait() メソッド

タスクが完了するまで待機します。

```cpp
void System::Threading::Tasks::Task::Wait()
```

## 参照

* クラス [CancellationToken](../../../system.threading/cancellationtoken/)
* クラス [Task](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)