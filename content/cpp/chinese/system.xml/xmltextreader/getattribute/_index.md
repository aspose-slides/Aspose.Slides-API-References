---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 参考
description: 返回具有指定名称的属性的值。
type: docs
weight: 495
url: /zh/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) 方法

返回具有指定名称的属性的值。

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的限定名称。 |

### 返回值

指定属性的值。如果未找到属性，则返回 **nullptr**。

## XmlTextReader::GetAttribute(String, String) 方法

返回具有指定本地名称和命名空间 URI 的属性的值。

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

指定属性的值。如果未找到属性，则返回 **nullptr**。此方法不会移动读取器。

## XmlTextReader::GetAttribute(int32_t) 方法

返回具有指定索引的属性的值。

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | **int32_t** | 属性的索引。索引从零开始。（第一个属性的索引为 0。） |

### 返回值

指定属性的值。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)