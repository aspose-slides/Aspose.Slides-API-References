---
title: TypeInfo()
second_title: Aspose.Slides for C++ API 参考
description: 默认构造函数（未设置类型）。
type: docs
weight: 40
url: /zh/system/typeinfo/typeinfo/
---
## TypeInfo::TypeInfo() 构造函数


默认构造函数（未设置类型）。

```cpp
System::TypeInfo::TypeInfo()
```

## TypeInfo::TypeInfo(std::nullptr_t) 构造函数


空对象构造函数（未设置类型）。

```cpp
System::TypeInfo::TypeInfo(std::nullptr_t)
```

## TypeInfo::TypeInfo(const char_t *) 构造函数


构造函数。

```cpp
System::TypeInfo::TypeInfo(const char_t *name)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const char_t * | 类型名称。 |

## TypeInfo::TypeInfo(const char_t *, uint32_t) 构造函数


构造函数。

```cpp
System::TypeInfo::TypeInfo(const char_t *name, uint32_t hash)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const char_t * | 类型名称。 |
| hash | **uint32_t** | 类型名称哈希。 |

## TypeInfo::TypeInfo(const std::type_info\&) 构造函数


构造函数。

```cpp
System::TypeInfo::TypeInfo(const std::type_info &info)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| info | const std::type_info\& | 关于类型的信息。 |

## 另见

* 类 [TypeInfo](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)