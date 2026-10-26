---
title: Wait()
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクトのロックを解放し、ロックが再取得されるまで現在のスレッドをブロックします。指定されたタイムアウト間隔が経過すると、スレッドは実行待ちキューに入ります。オプションで、待機前に同期コンテキストの同期ドメインを抜け、待機後にドメインを再取得します。未実装です。
type: docs
weight: 53
url: /ja/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) メソッド

オブジェクトのロックを解放し、ロックが再取得されるまで現在のスレッドをブロックします。指定されたタイムアウト間隔が経過すると、スレッドは実行待ちキューに入ります。オプションで、待機前に同期コンテキストの同期ドメインを抜け、待機後にドメインを再取得します。未実装です。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) メソッド

オブジェクトのロックを解放し、ロックが再取得されるまで現在のスレッドをブロックします。指定されたタイムアウト間隔が経過すると、スレッドは実行待ちキューに入ります。オプションで、待機前に同期コンテキストの同期ドメインを抜け、待機後にドメインを再取得します。未実装です。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) メソッド

オブジェクトのロックを解放し、ロックが再取得されるまで現在のスレッドをブロックします。指定されたタイムアウト間隔が経過すると、スレッドは実行待ちキューに入ります。未実装です。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) メソッド

オブジェクトのロックを解放し、ロックが再取得されるまで現在のスレッドをブロックします。指定されたタイムアウト間隔が経過すると、スレッドは実行待ちキューに入ります。未実装です。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) メソッド

オブジェクトのロックを解放し、ロックが再取得されるまで現在のスレッドをブロックします。未実装です。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [Monitor](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)