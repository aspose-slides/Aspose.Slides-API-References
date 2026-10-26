---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API リファレンス
description: このタスクの awaiter を取得し、await 式をサポートします。
type: docs
weight: 118
url: /ja/system.threading.tasks/resultvaluetask/getawaiter/
---
## ResultValueTask::GetAwaiter() const メソッド


このタスクの awaiter を取得し、await 式をサポートします。

```cpp
Runtime::CompilerServices::ResultValueTaskAwaiter<T> System::Threading::Tasks::ResultValueTask<T>::GetAwaiter() const
```


### 戻り値

ResultValueTaskAwaiter<T> このタスクの awaiter インスタンス。
## 備考



このメソッドは [ResultValueTask](../) と共に Await メソッドの使用を可能にします。 

## 参照

* クラス [ResultValueTaskAwaiter](../../../system.runtime.compilerservices/resultvaluetaskawaiter/)
* クラス [ResultValueTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)