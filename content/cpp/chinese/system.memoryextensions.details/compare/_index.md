---
title: Compare()
second_title: Aspose.Slides for C++ API 参考
description: 比较两个智能指针。
type: docs
weight: 1
url: /zh/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) 函数


比较两个智能指针。

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个智能指针的类型 |
| U | 第二个智能指针的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 第一个智能指针 |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | 第二个智能指针 |

### 返回值

[Comparison](../../system/comparison/) 结果 (0 表示相等, -1 表示 a < b, 1 表示 a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) 函数


比较两个算术值。

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 算术类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const T\& | 第一个值 |
| b | const T\& | 第二个值 |

### 返回值

[Comparison](../../system/comparison/) 结果 (0 表示相等, -1 表示 a < b, 1 表示 a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) 函数


比较智能指针与值。

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 智能指针指向的类型 |
| U | 值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 智能指针 |
| b | const U\& | 值 |

### 返回值

[Comparison](../../system/comparison/) 结果 (0 表示相等, -1 表示 a < b, 1 表示 a > b)

## 另请参阅

* 类型定义 [SharedPtr](../../system/sharedptr/)
* 命名空间 [System::MemoryExtensions::Details](../)
* 库 [Aspose.Slides](../../)