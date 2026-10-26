---
title: Thread()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。
type: docs
weight: 1
url: /ja/system.threading/thread/thread/
---
## Thread::Thread() constructor

コンストラクタ。

```cpp
System::Threading::Thread::Thread()
```

## Thread::Thread(ThreadStart) constructor

コンストラクタ。

```cpp
System::Threading::Thread::Thread(ThreadStart thread_function)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| thread_function | [ThreadStart](../../threadstart/) | スレッドで実行される関数。 |

## Thread::Thread(ParameterizedThreadStart) constructor

コンストラクタ。

```cpp
System::Threading::Thread::Thread(ParameterizedThreadStart thread_function)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| thread_function | [ParameterizedThreadStart](../../parameterizedthreadstart/) | スレッドで実行される関数。 |

## Thread::Thread(Thread\&) constructor

コピーコンストラクタ。

```cpp
System::Threading::Thread::Thread(Thread &t)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| t | [Thread](../)\& | [Thread](../) からデータをコピーする。 |

## 参照

* 型定義 [ThreadStart](../../threadstart/)
* 型定義 [ParameterizedThreadStart](../../parameterizedthreadstart/)
* クラス [Thread](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)