---
title: Join()
second_title: Aspose.Slides for C++ API リファレンス
description: 管理スレッドに参加します。必要に応じて無制限に待機します。
type: docs
weight: 196
url: /ja/system.threading/thread/join/
---
## Thread::Join() メソッド

管理スレッドに参加します。必要に応じて無制限に待機します。

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) メソッド

管理スレッドに参加します。制限付きで待機します。

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| millisecondsTimeout | int | ミリ秒単位の待機タイムアウト。 |

### 戻り値

スレッドが正常に結合された場合は true、タイムアウトを超えた場合は false。

## Thread::Join(TimeSpan) メソッド

管理スレッドに参加します。制限付きで待機します。

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | スレッドが終了するまで待機する時間を表す [TimeSpan](../../../system/timespan/)。 |

### 戻り値

スレッドが正常に結合された場合は true、タイムアウトを超えた場合は false。

## 関連項目

* クラス [Thread](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)