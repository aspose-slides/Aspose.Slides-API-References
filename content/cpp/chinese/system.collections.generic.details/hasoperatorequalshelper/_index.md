---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides for C++ API 参考
description: 帮助函数，用于确定特定类是否具有运算符 ==。
type: docs
weight: 235
url: /zh/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) 函数

帮助函数，用于确定特定类是否具有运算符 ==。

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要检查的类型。 |
| Dummy | 用于 SFINAE 魔术的虚拟参数。 |

### 返回值

如果存在 operator == 则返回 std::true_type，否则返回 false。

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) 函数

帮助函数，用于确定特定类是否具有运算符 ==。

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### 返回值

如果存在 operator == 则返回 std::true_type，否则返回 false。

## 另见

* 命名空间 [System::Collections::Generic::Details](../)
* 库 [Aspose.Slides](../../)