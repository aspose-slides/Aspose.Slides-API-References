---
title: Guid()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个表示全部为零的 GUID 的对象。
type: docs
weight: 1
url: /zh/system/guid/guid/
---
## Guid::Guid() 构造函数

构造一个表示全为零的 GUID 的对象。

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) 构造函数

构造一个表示为无符号 8 位整数数组的 GUID 的对象。

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含 GUID 各字节的字节数组 |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) 构造函数

构造一个表示为无符号 8 位整数数组视图的 GUID 的对象。

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | 包含 GUID 各字节的字节数组视图 |

## Guid::Guid(const String\&) 构造函数

构造一个使用字符串表示的 GUID 的对象。

```cpp
System::Guid::Guid(const String &g)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| g | const [String](../../string/)\& | 要由正在构造的对象表示的 GUID 的字符串表示形式 |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) 构造函数

根据指定的 GUID 组件构造 [Guid](../) 类的实例。

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | **int32_t** | GUID 的第 0-31 位 |
| b | **int16_t** | GUID 的第 32-47 位 |
| c | **int16_t** | GUID 的第 48-63 位 |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含 GUID 第 64-127 位的字节数组 |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) 构造函数

根据指定的 GUID 组件构造 [Guid](../) 类的实例。

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | **int32_t** | GUID 的第 0-31 位 |
| b | **int16_t** | GUID 的第 32-47 位 |
| c | **int16_t** | GUID 的第 48-63 位 |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | 包含 GUID 第 64-127 位的字节数组视图 |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) 构造函数

根据指定的无符号整数和字节构造 [Guid](../) 类的实例。

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | **int32_t** | GUID 的第 0-31 位 |
| b | **int16_t** | GUID 的第 32-47 位 |
| c | **int16_t** | GUID 的第 48-63 位 |
| d | **uint8_t** | GUID 的第 64-71 位 |
| e | **uint8_t** | GUID 的第 72-79 位 |
| f | **uint8_t** | GUID 的第 80-87 位 |
| g | **uint8_t** | GUID 的第 88-95 位 |
| h | **uint8_t** | GUID 的第 96-103 位 |
| i | **uint8_t** | GUID 的第 104-111 位 |
| j | **uint8_t** | GUID 的第 112-119 位 |
| k | **uint8_t** | GUID 的第 120-127 位 |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) 构造函数

根据指定的无符号整数和字节构造 [Guid](../) 类的实例。

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | **uint32_t** | GUID 的第 0-31 位 |
| b | **uint16_t** | GUID 的第 32-47 位 |
| c | **uint16_t** | GUID 的第 48-63 位 |
| d | **uint8_t** | GUID 的第 64-71 位 |
| e | **uint8_t** | GUID 的第 72-79 位 |
| f | **uint8_t** | GUID 的第 80-87 位 |
| g | **uint8_t** | GUID 的第 88-95 位 |
| h | **uint8_t** | GUID 的第 96-103 位 |
| i | **uint8_t** | GUID 的第 104-111 位 |
| j | **uint8_t** | GUID 的第 112-119 位 |
| k | **uint8_t** | GUID 的第 120-127 位 |

## Guid::Guid(const Guid\&) 构造函数

构造一个表示与指定对象相同 GUID 的对象。

```cpp
System::Guid::Guid(const Guid &guid)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| guid | const [Guid](../)\& | 用于复制 GUID 值的 [Guid](../) 对象 |

## 参见

* 类型别名 [ArrayPtr](../../arrayptr/)
* 类 [Guid](../)
* 类 [String](../../string/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)