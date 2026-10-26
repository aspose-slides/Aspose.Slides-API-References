---
title: operator==()
second_title: Aspose.Slides for C++ API 参考
description: 检查引用的对象是否为 null。
type: docs
weight: 53
url: /zh/system/weakreference_tmpl_t__end_tmpl/operator_equal_equal/
---
## WeakReference< T >::operator==(std::nullptr_t) const 方法

检查引用的对象是否为 null。

```cpp
bool System::WeakReference<T>::operator==(std::nullptr_t) const
```

### 返回值

如果引用的对象为 null 则返回 true， 否则返回 false。

## WeakReference< T >::operator==(const WeakReference\<T\>\&) const 方法

将引用的对象与另一个 WeakReference 类实例进行比较。

```cpp
bool System::WeakReference<T>::operator==(const WeakReference<T> &other) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [WeakReference](../weakreference/)\<T\>\& | [Object](../../object/) 用于比较。 |

### 返回值

如果比较的对象引用同一对象则返回 true，否则返回 false。

## 另请参见

* 方法 [WeakReference](../weakreference/)
* 类 [WeakReference< T >](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)