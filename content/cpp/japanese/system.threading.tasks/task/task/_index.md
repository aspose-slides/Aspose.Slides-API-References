---
title: Task()
second_title: Aspose.Slides for C++ API リファレンス
description: 実行するアクションを持つ Task を作成します。
type: docs
weight: 1
url: /ja/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) コンストラクタ

[Task](../) を作成し、実行するアクションを指定します。

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | 非同期に実行するアクション |

## Task::Task(const Action<>\&, const CancellationToken\&) コンストラクタ

[Task](../) を作成し、アクションとキャンセルトークンを指定します。

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | 非同期に実行するアクション |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | キャンセル要求を監視するトークン |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) コンストラクタ

[Task](../) を、状態を持つアクションと状態オブジェクトで作成します。

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | 状態オブジェクトを受け取るアクション |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | アクションに渡されるユーザー定義の状態オブジェクト |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) コンストラクタ

[Task](../) を、状態を持つアクション、状態、およびキャンセルトークンで作成します。

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | 状態オブジェクトを受け取るアクション |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | アクションに渡されるユーザー定義の状態オブジェクト |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | キャンセル要求を監視するトークン |

## Task::Task() コンストラクタ

未初期化タスクを作成するための内部コンストラクタです。

```cpp
System::Threading::Tasks::Task::Task()
```

## 参照

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Task](../)
* クラス [CancellationToken](../../../system.threading/cancellationtoken/)
* クラス [Object](../../../system/object/)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)