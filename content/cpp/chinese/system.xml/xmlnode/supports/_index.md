---
title: Supports()
second_title: Aspose.Slides for C++ API 参考
description: 测试 DOM 实现是否实现了特定功能。
type: docs
weight: 482
url: /zh/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) 方法

测试 DOM 实现是否实现了特定功能。

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| feature | [String](../../../system/string/) | 要测试的功能的包名称。此名称不区分大小写。 |
| version | [String](../../../system/string/) | 要测试的包名称的版本号。如果未指定版本（null），支持该功能的任何版本都会导致方法返回 true。 |

### 返回值

**true** 如果在指定版本中实现了该功能；否则 **false**。

## 备注

以下表格描述了返回 **true** 的组合。

| 特性 | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)