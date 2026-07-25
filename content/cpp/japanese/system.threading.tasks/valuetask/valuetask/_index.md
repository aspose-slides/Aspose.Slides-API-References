---
title: ValueTask()
second_title: Aspose.Slides for C++ API リファレンス
description: 空の、初期化されていない ValueTask を構築します。
type: docs
weight: 1
url: /ja/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() コンストラクタ


空の、初期化されていない [ValueTask](../) を構築します。

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## 備考



タスクは完了しておらず、結果を持ちません。結果を取得しようとすると例外がスローされます。 

## ValueTask::ValueTask(const TaskPtr\&) コンストラクタ


[Task](../../task/) の共有ポインタから [ValueTask](../) を構築します。

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | ラップするタスクです。空のタスクの場合は null にできます。 |
## 備考



提供されたタスクの状態を [ValueTask](../) が表します。 

## 参照

* 型定義 [TaskPtr](../../../system/taskptr/)
* クラス [ValueTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)