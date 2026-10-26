---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 参考
description: "在派生类中被重写时，获取具有指定 XmlReader::get_Name 值的属性的值。"
type: docs
weight: 599
url: /zh/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) 方法


在派生类中被重写时，获取具有指定 [XmlReader::get_Name](../get_name/) 值的属性的值。

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的限定名称。 |

### 返回值

指定属性的值。如果未找到属性或其值为 [String::Empty](../../../system/string/empty/)，则返回 **nullptr**。

## XmlReader::GetAttribute(String, String) 方法


在派生类中被重写时，获取具有指定 [XmlReader::get_LocalName](../get_localname/) 和 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值的属性的值。

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

指定属性的值。如果未找到属性或其值为 [String::Empty](../../../system/string/empty/)，则返回 **nullptr**。此方法不会移动读取器。

## XmlReader::GetAttribute(int32_t) 方法


在派生类中被重写时，获取具有指定索引的属性的值。

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | **int32_t** | 属性的索引。索引从零开始。（第一个属性的索引为 0。） |

### 返回值

指定属性的值。此方法不会移动读取器。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)