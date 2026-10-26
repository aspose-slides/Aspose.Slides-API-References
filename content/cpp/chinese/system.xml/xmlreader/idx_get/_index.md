---
title: idx_get()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中重写时，获取具有指定索引的属性的值。
type: docs
weight: 612
url: /zh/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) 方法

在派生类中重写时，获取具有指定索引的属性的值。

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | **int32_t** | 属性的索引。 |

### 返回值

指定属性的值。

## XmlReader::idx_get(String) 方法

在派生类中重写时，获取具有指定 [XmlReader::get_Name](../get_name/) 值的属性的值。

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的限定名称。 |

### 返回值

指定属性的值。如果未找到属性，则返回 **nullptr**。

## XmlReader::idx_get(String, String) 方法

在派生类中重写时，获取具有指定 [XmlReader::get_LocalName](../get_localname/) 和 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值的属性的值。

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

指定属性的值。如果未找到属性，则返回 **nullptr**。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)