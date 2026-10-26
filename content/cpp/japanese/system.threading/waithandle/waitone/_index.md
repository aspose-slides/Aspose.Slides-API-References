---
title: WaitOne()
second_title: Aspose.Slides for C++ API リファレンス
description: ハンドルが発火するまで無制限に待機します。
type: docs
weight: 27
url: /ja/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() メソッド

ハンドルが発火するまで無制限に待機します。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### 戻り値

常に true を返します（タイムアウトは発生しません）。

## WaitHandle::WaitOne(int) メソッド

ハンドルが発火するまで待機します。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) は待機時間（ミリ秒）です；-1 は無限待機を意味し、0 はチェックして戻ることを意味し、正の値はタイムアウトとなります。 |

### 戻り値

ハンドルが発火した場合は true、タイムアウトした場合は false を返します。

## WaitHandle::WaitOne(TimeSpan) メソッド

ハンドルが発火するまで待機します。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | 待機するミリ秒数を表す [System::TimeSpan](../../../system/timespan/)、または無期限に待機することを表す -1 ミリ秒を示す [System::TimeSpan](../../../system/timespan/)。 |

### 戻り値

ハンドルが発火した場合は true、タイムアウトした場合は false を返します。

## WaitHandle::WaitOne(int, bool) メソッド

ハンドルが発火するまで待機します。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) は待機時間（ミリ秒）です；-1 は無限待機を意味し、0 はチェックして戻ることを意味し、正の値はタイムアウトとなります。 |
| exitContext | **bool** | true の場合、待機する前にハンドルのロックを解除してから待機すべきです。 |

### 戻り値

ハンドルが発火した場合は true、タイムアウトした場合は false を返します。

## 関連項目

* クラス [WaitHandle](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)