---
title: get_XmlSpace()
second_title: Aspose.Slides for C++ API 参考
description: "当在派生类中重写时，获取表示当前 xml:space 范围的 XmlSpace。"
type: docs
weight: 27
url: /zh/system.xml/xmlwriter/get_xmlspace/
---
## XmlWriter::get_XmlSpace() 方法


When overridden in a derived class, gets an XmlSpace representing the current **xml:space** scope.

```cpp
virtual System::Xml::XmlSpace System::Xml::XmlWriter::get_XmlSpace()
```


### 返回值

An XmlSpace representing the current **xml:space** scope.



| 值 | 含义 |
| --- | --- |
| `None`| 这是默认值，如果不存在 `xml:space` 范围。 |
| `Default`| 当前范围是 `xml:space="default"`。 |
| `Preserve`| 当前范围是 `xml:space="preserve"`。 |


## 另见

* Enum [XmlSpace](../../xmlspace/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* Library [Aspose.Slides](../../../)