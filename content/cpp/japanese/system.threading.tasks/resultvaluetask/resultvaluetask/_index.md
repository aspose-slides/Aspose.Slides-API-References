---
title: ResultValueTask()
second_title: Aspose.Slides for C++ API リファレンス
description: 空の、初期化されていない ResultValueTask を構築します。
type: docs
weight: 1
url: /ja/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() コンストラクタ

空の、初期化されていない [ResultValueTask](../) を構築します。

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## 備考

タスクは完了しておらず、結果を持ちません。結果を取得しようとすると例外がスローされます。

## ResultValueTask::ResultValueTask(const T\&) コンストラクタ

指定された結果で完了した [ResultValueTask](../) を構築します。

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| result | const T\& | 完了したタスクにラップする結果の値。 |

## 備考

これにより、すぐに値を返す正常に完了したタスクが作成されます。

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) コンストラクタ

ResultTask<T> への共有ポインタから [ResultValueTask](../) を構築します。

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | ラップするタスク。空のタスクの場合は null にできます。 |

## 備考

[ResultValueTask](../) は提供されたタスクの状態と結果を表します。

## 参照

* 型定義 [RTaskPtr](../../../system/rtaskptr/)
* クラス [ResultValueTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)