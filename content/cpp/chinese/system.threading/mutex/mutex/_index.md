---
title: Mutex()
second_title: Aspose.Slides C++ API 参考
description: 构造未拥有的互斥体。
type: docs
weight: 1
url: /zh/system.threading/mutex/mutex/
---
## Mutex::Mutex() 构造函数

构造一个未拥有的互斥体。

```cpp
System::Threading::Mutex::Mutex()
```

## Mutex::Mutex(bool) 构造函数

构造函数。

```cpp
System::Threading::Mutex::Mutex(bool initiallyOwned)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| initiallyOwned | **bool** | 如果为 true，则正在构造的互斥体最初被拥有。 |

## Mutex::Mutex(bool, const String\&) 构造函数

构造函数。

```cpp
System::Threading::Mutex::Mutex(bool initiallyOwned, const String &name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| initiallyOwned | **bool** | 如果为 true，则正在构造的互斥体最初被拥有。 |
| name | const [String](../../../system/string/)\& | 互斥体的名称。 |

## 另请参见

* 类 [Mutex](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Threading](../../)
* Library [Aspose.Slides](../../../)