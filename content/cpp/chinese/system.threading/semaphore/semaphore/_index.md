---
title: Semaphore()
second_title: Aspose.Slides C++ API 参考
description: 创建未命名的信号量。
type: docs
weight: 1
url: /zh/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) 构造函数

创建未命名的信号量。

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| initialCount | int | 活动条目的初始计数。 |
| maximumCount | int | 最大允许的条目计数。 |

## Semaphore::Semaphore(int, int, const String\&) 构造函数

创建已命名的信号量。

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| initialCount | int | 活动条目的初始计数。 |
| maximumCount | int | 最大允许的条目计数。 |
| name | const [String](../../../system/string/)\& | [Semaphore](../) 名称。 |

## Semaphore::Semaphore(int, int, const String\&, bool\&) 构造函数

创建已命名的信号量。

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| initialCount | int | 活动条目的初始计数。 |
| maximumCount | int | 最大允许的条目计数。 |
| name | const [String](../../../system/string/)\& | [Semaphore](../) 名称。 |
| createdNew | **bool**\& | 引用变量，如果信号量被创建则设为 true，如果使用了同名的已有信号量则设为 false。 |

## 另请参见

* 类 [Semaphore](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)