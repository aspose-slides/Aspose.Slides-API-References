---
title: idx_get()
second_title: Aspose.Slides for C++ API 参考
description: 返回具有指定索引的属性。
type: docs
weight: 1
url: /zh/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) 方法

返回具有指定索引的属性。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | **int32_t** | 属性的索引。 |

### 返回值

指定索引处的属性。

## XmlAttributeCollection::idx_get(const String\&) 方法

返回具有指定名称的属性。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 属性的限定名称。 |

### 返回值

具有指定名称的属性。如果属性不存在，此方法返回 **nullptr**。

## XmlAttributeCollection::idx_get(const String\&, const String\&) 方法

返回具有指定本地名称和命名空间统一资源标识符（URI）的属性。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性的本地名称。 |
| namespaceURI | const [String](../../../system/string/)\& | 属性的命名空间 URI。 |

### 返回值

具有指定本地名称和命名空间 URI 的属性。如果属性不存在，此方法返回 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlAttribute](../../xmlattribute/)
* 类 [XmlAttributeCollection](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)