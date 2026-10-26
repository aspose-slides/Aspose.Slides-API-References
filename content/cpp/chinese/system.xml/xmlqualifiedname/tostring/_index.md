---
title: ToString()
second_title: Aspose.Slides for C++ API 参考
description: 返回 XmlQualifiedName 的字符串值。
type: docs
weight: 79
url: /zh/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const 方法


返回 [XmlQualifiedName](../) 的字符串值。

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### 返回值

以 **namespace:localname** 格式的 [XmlQualifiedName](../) 的字符串值。如果对象没有定义命名空间，此方法仅返回本地名称。

## XmlQualifiedName::ToString(const String\&, const String\&) 方法


返回 [XmlQualifiedName](../) 的字符串值。

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 对象的名称。 |
| ns | const [String](../../../system/string/)\& | 对象的命名空间。 |

### 返回值

以 **namespace:localname** 格式的 [XmlQualifiedName](../) 的字符串值。如果对象没有定义命名空间，此方法仅返回本地名称。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlQualifiedName](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)