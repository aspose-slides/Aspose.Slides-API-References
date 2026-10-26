---
title: ReadElementContentAsObject()
second_title: Aspose.Slides C++ API 参考
description: 读取当前元素并将内容作为对象返回。
type: docs
weight: 469
url: /zh/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() 方法


读取当前元素并将内容作为 [Object](../../../system/object/) 返回。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### 返回值

装箱对象的最合适类型。[XmlReader::get_ValueType](../get_valuetype/) 值决定合适的类型。如果内容被键入为列表类型，此方法返回相应类型的装箱对象数组。

## XmlReader::ReadElementContentAsObject(String, String) 方法


检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为 [Object](../../../system/object/) 返回。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 元素的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 元素的命名空间 URI。 |

### 返回值

装箱对象的最合适类型。[XmlReader::get_ValueType](../get_valuetype/) 值决定合适的类型。如果内容被键入为列表类型，此方法返回相应类型的装箱对象数组。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [XmlReader](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)