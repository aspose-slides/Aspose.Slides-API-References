---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API リファレンス
description: パラメータなしのコールバックがあるキューに作業項目を投入します。
type: docs
weight: 14
url: /ja/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) メソッド

パラメータなしのコールバックがあるキューに作業項目を投入します。

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | ジョブとして使用されるコールバック関数。 |

### 戻り値

常に true を返します。

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) メソッド

パラメータなしのコールバックがあるキューに作業項目を投入します。

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | ジョブとして使用されるコールバック関数。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | ジョブ関数のパラメータ。 |

### 戻り値

常に true を返します。

## 参照

* 型定義 [WaitCallback](../../waitcallback/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ThreadPool](../)
* クラス [Object](../../../system/object/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)