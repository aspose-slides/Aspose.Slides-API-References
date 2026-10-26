---
title: TryEnter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたオブジェクトに対して排他ロックを取得しようとします。実装されていません。
type: docs
weight: 27
url: /ja/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) メソッド


指定されたオブジェクトに対して排他ロックを取得しようとします。実装されていません。

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) メソッド


指定されたオブジェクトに対して排他ロックを取得し、ロックが取得されたかどうかを示す値を原子的に設定します。

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) メソッド


指定されたミリ秒数の間、指定されたオブジェクトに対して排他ロックを取得しようとします。実装されていません。

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) メソッド


指定された時間の間、指定されたオブジェクトに対して排他ロックを取得しようとします。実装されていません。

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) メソッド


指定された時間の間、指定されたオブジェクトに対して排他ロックを取得し、ロックが取得されたかどうかを示す値を原子的に設定します。

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) メソッド


指定された時間の間、指定されたオブジェクトに対して排他ロックを取得し、ロックが取得されたかどうかを示す値を原子的に設定します。

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [Monitor](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)