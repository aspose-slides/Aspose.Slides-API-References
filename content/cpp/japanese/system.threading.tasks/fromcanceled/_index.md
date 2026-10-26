---
title: FromCanceled()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたトークンによるキャンセルで完了したタスクを作成します。
type: docs
weight: 118
url: /ja/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) 関数


指定されたトークンによるキャンセルで完了したタスクを作成します。

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | タスクがキャンセルされた原因となるキャンセルトークン。 |

### 戻り値

キャンセルされたタスク。

## 参照

* Typedef [TaskPtr](../../system/taskptr/)
* クラス [CancellationToken](../../system.threading/cancellationtoken/)
* 名前空間 [System::Threading::Tasks](../)
* ライブラリ [Aspose.Slides](../../)