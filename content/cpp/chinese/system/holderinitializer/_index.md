---
title: HolderInitializer
second_title: Aspose.Slides for C++ API 参考
description: 此类用于获取对象实例的持久引用，无论它是左值还是右值。要获取此类引用，请使用 'HoldIfTemporary' 方法，它有三个重载。其中两个以右值为参数，只返回对其的引用。第三个相反，以左值为参数，进行指针复制，然后返回对该复制的引用。此外，类还有 'Hold' 方法，可无条件地持有传入的值（用于复制局部栈变量或其子引用的值）。
type: docs
weight: 1613
url: /zh/system/holderinitializer/
---
## HolderInitializer 结构体

This 类 用于获取对象实例的持久引用，无论它是左值还是右值。要获取此类引用，请使用 'HoldIfTemporary' 方法，它有三种重载。其中两种以右值为参数，并直接返回对其的引用。第三种则相反，以左值为参数，进行指针拷贝，然后返回对该拷贝的引用。此外，类还有 'Hold' 方法，可无条件地持有传入的值（用于拷贝局部栈变量或其子引用的值）。

```cpp
template<typename T,bool>class HolderInitializer
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要持有的对象的类型。 |
| R | 如果 T 是引用类型（[SmartPtr](../smartptr/) 特化或 [System::String](../string/) 类型）且确实需要保持临时引用，则为 true；否则为 false。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | 将传入的左值复制到持有者，然后返回持有者引用。调用者应使用此方法无条件地持有传入的值。 |
|  [HolderInitializer](./holderinitializer/)(T\&) | 使用传入的引用初始化持有者引用。 |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | 返回对右值的引用（const） |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | 返回对右值的引用（非 const） |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | 将传入的左值复制到持有者，然后返回持有者引用。 |

## 另请参见

* Namespace [System](../)
* Library [Aspose.Slides](../../)