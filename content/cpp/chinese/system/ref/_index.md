---
title: Ref()
second_title: Aspose.Slides for C++ API 参考
description: 创建对 DynamicWeakPtr 对象的引用。翻译器在按引用传递函数参数时使用。
type: docs
weight: 2419
url: /zh/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) 函数


创建对 [DynamicWeakPtr](../dynamicweakptr/) 对象的引用。翻译器在按引用传递函数参数时使用。

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被指向类型。 |
| trunkMode | 智能指针本身的模式。 |
| weakLeafs | 必须调用 SetTemplateWeakPtr 方法的模板参数索引。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | 用于创建引用的智能指针。 |

### 返回值

智能指针引用。

## System::Ref(T\&) 函数


帮助函数，用于获取对象的引用。用于确保在赋值后 [System::DynamicWeakPtr](../dynamicweakptr/) 更新被引用的对象。

```cpp
template<typename T> T & System::Ref(T &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要创建引用的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T\& | 用于创建引用的值。 |

### 返回值

对传递给此函数的值的引用。

## 参见

* 类 [DynamicWeakPtr](../dynamicweakptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)