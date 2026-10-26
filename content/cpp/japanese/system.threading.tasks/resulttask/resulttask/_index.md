---
title: ResultTask()
second_title: Aspose.Slides for C++ API リファレンス
description: 関数が値を返す ResultTask を構築します。
type: docs
weight: 1
url: /ja/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) コンストラクタ

[ResultTask](../) を、値を返す関数で構築します。

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | 非同期で実行され、結果を返す関数 |

## ResultTask::ResultTask() コンストラクタ

内部実装です。ユーザーコードでは使用しないでください。

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## 備考

未初期化の結果タスクを作成するための内部コンストラクタ

## ResultTask::ResultTask(const T\&) コンストラクタ

指定された結果で結果タスクを作成するための内部コンストラクタ。

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## 参照

* クラス [Func](../../../system/func/)
* クラス [ResultTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)