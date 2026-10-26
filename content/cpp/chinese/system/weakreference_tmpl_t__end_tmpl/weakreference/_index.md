---
title: WeakReference()
second_title: Aspose.Slides C++ API 参考
description: 默认构造函数。
type: docs
weight: 1
url: /zh/system/weakreference_tmpl_t__end_tmpl/weakreference/
---
## WeakReference< T >::WeakReference() method

默认构造函数。

```cpp
System::WeakReference<T>::WeakReference()
```

## WeakReference< T >::WeakReference(std::nullptr_t) method

来自 nullptr 的构造函数。

```cpp
System::WeakReference<T>::WeakReference(std::nullptr_t)
```

## WeakReference< T >::WeakReference(const SmartPtr\<T\>\&) method

初始化 WeakReference 类的新实例，引用指定的对象。

```cpp
System::WeakReference<T>::WeakReference(const SmartPtr<T> &data)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<T\>\& | [Object](../../object/) 用于存储。 |

## WeakReference< T >::WeakReference(const SmartPtr\<T\>\&, bool) method

初始化 WeakReference 类的新实例，引用指定的对象。

```cpp
System::WeakReference<T>::WeakReference(const SmartPtr<T> &data, bool trackResurrection)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<T\>\& | [Object](../../object/) 用于存储。 |
| trackResurrection | **bool** | 已忽略。 |

## 另请参见

* 类 [WeakReference< T >](../)
* 类 [SmartPtr](../../smartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)