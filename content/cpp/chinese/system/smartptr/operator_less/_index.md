---
title: operator<()
second_title: Aspose.Slides for C++ API 参考
description: 为 SmartPtr 类提供较小比较语义。
type: docs
weight: 235
url: /zh/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const method


提供对 [SmartPtr](../) 类的较小比较语义。

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


### 模板参数

| Parameter | Description |
| --- | --- |
| Y | Type of pointer to compare current one to. |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| p | Y * | Pointer to compare current one to. |

### 返回值

True if the object referenced by [SmartPtr](../) is 'less' than p and false otherwise.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


提供对 [SmartPtr](../) 类的较小比较语义。

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


### 模板参数

| Parameter | Description |
| --- | --- |
| Y | Type of pointer to compare current one to. |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Pointer to compare current one to. |

### 返回值

True if the object referenced by [SmartPtr](../) is 'less' than x and false otherwise.

## 另请参见

* 类 [SmartPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)