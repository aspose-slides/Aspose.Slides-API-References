---
title: BaseDictionary()
second_title: Aspose.Slides C++ API 参考
description: 创建空的数据结构。
type: docs
weight: 14
url: /zh/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() 构造函数


创建空的数据结构。

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) 构造函数


转发构造函数，将参数推送到底层 map 构造函数。

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| Args | 要转发到 map 的参数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | int | 参数用于转发到底层 map。 |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) 构造函数


复制构造函数。

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| Args | map 构造函数参数的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) 用于复制数据来源。 |
| args | const Args\&... | 参数用于转发到底层 map 构造函数。 |

## BaseDictionary::BaseDictionary(BaseType *) 构造函数


复制构造函数。

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) 用于复制数据来源。 |

## 另请参阅

* 类型别名 [BaseType](../basetype/)
* 类 [BaseDictionary](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)