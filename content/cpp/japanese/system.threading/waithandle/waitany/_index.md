---
title: WaitAny()
second_title: Aspose.Slides for C++ API リファレンス
description: ハンドルのいずれかが発火するのを待ちます。
type: docs
weight: 14
url: /ja/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) メソッド

ハンドルのいずれかが発火するのを待ちます。

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 待機対象のハンドル。 |
| millisecondsTimeout | int | [Timeout](../../timeout/) 待機時間（ミリ秒単位）；-1 は無限待機、0 はチェックして戻り、正の値はタイムアウトです。 |

### 戻り値

ハンドルがいずれか発火した場合は True、タイムアウトが超過した場合は false を返します。

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) メソッド

ハンドルのいずれかが発火するのを待ちます。

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 待機対象のハンドル。 |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) は待機するミリ秒数を表し、[System::TimeSpan](../../../system/timespan/) は -1 ミリ秒（無期限待機）を表します。 |

### 戻り値

ハンドルがいずれか発火した場合は True、タイムアウトが超過した場合は false を返します。

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) メソッド

ハンドルのいずれかが発火するのを待ちます。

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 待機対象のハンドル。 |

### 戻り値

waitHandles のすべての要素がシグナルを受け取ったときに True を返し、そうでない場合はメソッドは決して戻りません。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [WaitHandle](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)