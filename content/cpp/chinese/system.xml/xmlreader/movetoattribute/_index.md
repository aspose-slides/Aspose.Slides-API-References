---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 参考
description: "当在派生类中被重写时，移动到具有指定 XmlReader::get_Name 值的属性。"
type: docs
weight: 625
url: /zh/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) 方法

当在派生类中被重写时，移动到具有指定 [XmlReader::get_Name](../get_name/) 值的属性。

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的限定名称。 |

### 返回值

**true** 如果找到属性；否则为 **false**。如果为 **false**，读取器的位置不会改变。

## XmlReader::MoveToAttribute(String, String) 方法

当在派生类中被重写时，移动到具有指定 [XmlReader::get_LocalName](../get_localname/) 和 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值的属性。

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的本地名称。 |
| ns | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

**true** 如果找到属性；否则为 **false**。如果为 **false**，读取器的位置不会改变。

## XmlReader::MoveToAttribute(int32_t) 方法

当在派生类中被重写时，移动到具有指定索引的属性。

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | **int32_t** | 属性的索引。 |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)