---
title: InsertAfter()
second_title: Aspose.Slides C++ API 参考
description: 在指定的参考属性之后立即插入指定的属性。
type: docs
weight: 66
url: /zh/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) 方法

在指定的参考属性之后立即插入指定的属性。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 要插入的属性。 |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 参考属性。**newNode** 放置在 **refNode** 之后。 |

### 返回值

要插入到集合中的[XmlAttribute](../../xmlattribute/)。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlAttribute](../../xmlattribute/)
* 类 [XmlAttributeCollection](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)