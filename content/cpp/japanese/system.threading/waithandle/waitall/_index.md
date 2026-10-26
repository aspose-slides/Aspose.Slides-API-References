---
title: WaitAll()
second_title: Aspose.Slides for C++ API リファレンス
description: すべてのハンドルが発火するのを待ちます。
type: docs
weight: 1
url: /ja/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) メソッド

すべてのハンドルが発火するのを待ちます。

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 待機対象のハンドル。 |
| millisecondsTimeout | int | [Timeout](../../timeout/) 待機時間（ミリ秒単位）。-1 は無限待機、0 はチェックしてすぐ戻り、正の値はタイムアウトを表します。 |

### 戻り値

すべてのハンドルが発火した場合は true、タイムアウトが発生した場合は false が返されます。

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) メソッド

すべてのハンドルが発火するのを待ちます。

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 待機対象のハンドル。 |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) は待機時間（ミリ秒）を表すもので、[System::TimeSpan](../../../system/timespan/) は無期限に待機するための -1 ミリ秒を表すものです。 |

### 戻り値

すべてのハンドルが発火した場合は true、タイムアウトが発生した場合は false が返されます。

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) メソッド

すべてのハンドルが発火するのを待ちます。

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 待機対象のハンドル。 |

### 戻り値

waitHandles のすべての要素がシグナルを受信したときに true を返します。それ以外の場合、メソッドは決して戻りません。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)