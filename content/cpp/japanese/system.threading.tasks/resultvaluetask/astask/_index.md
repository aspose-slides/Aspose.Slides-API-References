---
title: AsTask()
second_title: Aspose.Slides の C++ API リファレンス
description: この ResultValueTask を ResultTask<T> への共有ポインタに変換します。
type: docs
weight: 79
url: /ja/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const メソッド

この [ResultValueTask](../) を ResultTask<T> への共有ポインタに変換します。

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### 戻り値

RTaskPtr<T> この操作を表す ResultTask<T> への共有ポインタです。

## 備考

[ResultValueTask](../) に直接結果が含まれている場合、その結果で完了したタスクを作成します。タスクが含まれている場合、そのタスクへの共有ポインタを返します。

## 参照

* 型定義 [RTaskPtr](../../../system/rtaskptr/)
* クラス [ResultValueTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)