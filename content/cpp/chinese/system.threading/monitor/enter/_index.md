---
title: Enter()
second_title: Aspose.Slides for C++ API 参考
description: 获取对指定对象的独占锁。
type: docs
weight: 1
url: /zh/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) 方法

获取对指定对象的独占锁。

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要获取监视器锁的对象。 |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) 方法

获取对指定对象的独占锁，并原子地设置一个指示锁是否已被获取的值。

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [Monitor](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)