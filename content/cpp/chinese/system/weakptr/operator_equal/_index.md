---
title: operator=()
second_title: Aspose.Slides for C++ API 参考
description: 将值分配给弱指针。调用 SmartPtr_ 的特定赋值运算符。
type: docs
weight: 14
url: /zh/system/weakptr/operator_equal/
---
## WeakPtr::operator=(Q\&&) 方法

将值分配给弱指针。调用 SmartPtr_ 的特定赋值运算符。

```cpp
template<typename Q> WeakPtr & System::WeakPtr<T>::operator=(Q &&value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | [System::SmartPtr](../../smartptr/) 赋值运算符支持的参数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | Q\&& | 用于复制被指对象值的指针。 |

## 另请参见

* 类 [WeakPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)