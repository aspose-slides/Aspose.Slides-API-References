---
title: HasFeature()
second_title: Aspose.Slides for C++ API 参考
description: 测试 Document Object Model (DOM) 实现是否实现特定功能。
type: docs
weight: 14
url: /zh/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String&, const String&) 方法

测试 Document [Object](../../../system/object/) Model (DOM) 实现是否实现特定功能。

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)& | 要测试的功能的包名称。此名称不区分大小写。 |
| strVersion | const [String](../../../system/string/)& | 要测试的包名称的版本号。如果未指定版本 (**nullptr**)，则支持任何版本的该功能会导致方法返回 **true**。 |

### 返回值

**true** 如果在指定版本中实现了该功能；否则 **false**。

## 备注

以下表格显示了导致 **HasFeature** 返回 **true** 的组合。

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlImplementation](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)