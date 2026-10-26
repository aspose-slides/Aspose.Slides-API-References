---
title: get_NameTable()
second_title: Aspose.Slides C++ API 参考
description: 返回用于原子化字符串比较的 XmlNameTable。
type: docs
weight: 1
url: /zh/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() 方法

返回用于原子化字符串比较的 [XmlNameTable](../../xmlnametable/)。

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### 返回值

该 [XmlNameTable](../../xmlnametable/) 存储所有由使用此 [XmlReaderSettings](../) 对象创建的 [XmlReader](../../xmlreader/) 实例使用的原子化字符串。默认值为 **nullptr**。如果该值为 **nullptr**，则创建的 [XmlReader](../../xmlreader/) 实例将使用新的空 [NameTable](../../nametable/)。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNameTable](../../xmlnametable/)
* 类 [XmlReaderSettings](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)