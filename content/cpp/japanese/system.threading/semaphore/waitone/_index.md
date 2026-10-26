---
title: WaitOne()
second_title: Aspose.Slides for C++ API リファレンス
description: セマフォをロックします。必要に応じて無制限の待機を行います。
type: docs
weight: 40
url: /ja/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() メソッド

セマフォをロックします。必要に応じて無制限の待機を行います。

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### 戻り値

セマフォがロックされるまで戻らないため、常に true を返します。

## Semaphore::WaitOne(int) メソッド

セマフォをロックします。必要に応じて待機を行います。

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| millisecondsTimeout | int | ミリ秒単位の待機タイムアウト。 |

### 戻り値

セマフォがロックされた場合は true、タイムアウトが超過した場合は false を返します。

## 参照

* クラス [Semaphore](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)