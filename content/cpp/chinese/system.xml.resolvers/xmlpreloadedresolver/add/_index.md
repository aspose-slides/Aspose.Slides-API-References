---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 将字节数组添加到 XmlPreloadedResolver 存储并映射到 URI。如果存储中已存在相同 URI 的映射，则覆盖现有映射。
type: docs
weight: 79
url: /zh/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) 方法

将字节数组添加到 [XmlPreloadedResolver](../) 存储并映射到 URI。如果存储中已存在相同 URI 的映射，则覆盖现有映射。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 要添加到 [XmlPreloadedResolver](../) 存储的数��的 URI。 |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 与提供的 URI 对应的字节数组。 |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

将字节数组添加到 [XmlPreloadedResolver](../) 存储并映射到 URI。如果存储中已存在相同 URI 的映射，则覆盖现有映射。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 要添加到 [XmlPreloadedResolver](../) 存储的数��的 URI。 |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 与提供的 URI 对应的字节数组。 |
| offset | **int32_t** | 在提供的字节数组中数据开始的偏移量。 |
| count | **int32_t** | 从字节数组中读取的字节数，从提供的偏移量开始。 |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) 方法

将 Stream 添加到 [XmlPreloadedResolver](../) 存储并映射到 URI。如果存储中已存在相同 URI 的映射，则覆盖现有映射。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 要添加到 [XmlPreloadedResolver](../) 存储的数��的 URI。 |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 与提供的 URI 对应的 Stream。 |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) 方法

将预加载数据的字符串添加到 [XmlPreloadedResolver](../) 存储并映射到 URI。如果存储中已存在相同 URI 的映射，则覆盖现有映射。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 要添加到 [XmlPreloadedResolver](../) 存储的数��的 URI。 |
| value | const [String](../../../system/string/)\& | 一个 [String](../../../system/string/)，其数据对应于提供的 URI。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Uri](../../../system/uri/)
* 类 [XmlPreloadedResolver](../)
* 类 [Stream](../../../system.io/stream/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::Resolvers](../../)
* 库 [Aspose.Slides](../../../)