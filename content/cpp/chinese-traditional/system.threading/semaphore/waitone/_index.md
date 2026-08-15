---
title: WaitOne()
second_title: Aspose.Slides for C++ API 參考
description: 鎖定信號量。如果有需要，執行無限制的等待。
type: docs
weight: 40
url: /zh-hant/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() 方法

鎖定信號量。如果有需要，會執行無限制的等待。

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### 返回值

始終返回 true，因為在信號量被鎖定之前不會返回。

## Semaphore::WaitOne(int) 方法

鎖定信號量。如果有需要，會執行等待。

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | 以毫秒為單位的等待逾時時間。 |

### 返回值

如果信號量被鎖定則返回 true；如果逾時則返回 false。

## 另見

* 類別 [Semaphore](../)
* 命名空間 [System::Threading](../../)
* 程式庫 [Aspose.Slides](../../../)