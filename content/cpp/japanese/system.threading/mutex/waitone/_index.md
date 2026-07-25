---
title: WaitOne()
second_title: Aspose.Slides for C++ API リファレンス
description: ミューテックスをロックします。必要に応じて無制限に待機します。
type: docs
weight: 53
url: /ja/system.threading/mutex/waitone/
---
## Mutex::WaitOne() メソッド

ミューテックスをロックします。必要に応じて無制限の待機を行います。

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### 戻り値

ミューテックスがロックされるまで戻らないため、常に true を返します。

## Mutex::WaitOne(int) メソッド

ミューテックスをロックします。必要に応じて待機を行います。

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| millisecondsTimeout | int | ミリ秒単位の待機タイムアウト。 |

### 戻り値

ミューテックスがロックされた場合は true を、タイムアウトが超過した場合は false を返します。

## Mutex::WaitOne(TimeSpan) メソッド

ミューテックスをロックします。必要に応じて待機を行います。

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/)は待機するミリ秒数を表し、[System::TimeSpan](../../../system/timespan/)は -1 ミリ秒（無期限）を表します。 |

### 戻り値

ミューテックスがロックされた場合は true を、タイムアウトが超過した場合は false を返します。

## 参照

* クラス [Mutex](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)