---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API リファレンス
description: この結果タスクの awaiter を取得し、Await とともに使用します。
type: docs
weight: 53
url: /ja/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const メソッド


Await とともに使用するための、この結果タスクの awaiter を取得します。

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### 戻り値

Runtime::CompilerServices::ResultTaskAwaiter<T> 結果を返す awaiter インスタンス
## 備考



await されると、コルーチンは結果値が利用可能な状態で再開します。

## 参照

* クラス [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* クラス [ResultTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)